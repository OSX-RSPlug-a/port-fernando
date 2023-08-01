---
title: Gatus tool tutorial
description: Some tricks commands
date: '2023-4-26'
categories:
  - Monitoring tool
  - Gatus
  - yaml
  - Docker
  - Docker-compose
published: true
---


![Svelte](pexels-sabrina-gelbart-249798.jpg)

## Topics

- Monitoring tool
- Docker

Gatus is a health dashboard, or like status page, 
that gives you the ability to monitor your 
services using HTTP, ICMP, TCP, and even DNS 
queries as well as evaluate the result of said 
queries by using a list of conditions on values 
like the status code, the response time, the 
certificate expiration, the body and many others. 
 The icing on top is that each of these health 
 checks can be paired with alerting via Slack, 
 PagerDuty, Discord, Twilio and more.

 Ex. with docker:

 - Create 2 files, gatus-stack.yaml and config.yaml:

```yaml
    version: '3.3'
    services:
    gatus:
        container_name: gatus
        image: twinproduction/gatus:latest
        restart: always
        ports:
        - 19998:19998
        volumes:
        - ./config.yaml:/config/config.yaml
        networks:
        - metrics
    networks:
    metrics:
        driver: bridge
``` 

---

```yaml
    services:
    - name: Google site
        url: https://google.com/
        interval: 1m
        conditions:
        - "[STATUS] == 200"

    - name: DuckDuckgo
        url: https://duckduckgo.com
        interval: 1m
        conditions:
        - "[STATUS] == 200"
```

- running the stack:

```bash
 docker-compose -f gatus-stack up -d
```


```ts
function greet(name: string) {
	console.log(`Hey ${name}! 👋`)
}
```