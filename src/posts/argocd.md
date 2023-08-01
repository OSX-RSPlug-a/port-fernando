---
title: ArgoCD installation tutorial
description: Argocd installation mini tutorial
date: '2023-4-26'
categories:
  - Kubernetes
  - Argocd
  - Tutorial
published: true
---

![Svelte](pexels-tima-miroshnichenko-5380664.jpg)


## Topics

- ArgoCD

Argo CD is a declarative, GitOps continuous 
delivery tool for Kubernetes. 

Once you have the cluster it can be add.

- 1 create a namespace for the stack

```bash
 kubectl create namespace argocd
```

- 2 then apply by raw or coping the yaml

```bash
 kubectl apply -n argocd -f https://raw.githubusercontent.com/argoproj/argo-cd/stable/manifests/core-install.yaml
```

Access the ui:

```bash
 kubectl port-forward svc/argocd-server -n argocd 8080:443
```

```ts
function greet(name: string) {
	console.log(`Hey ${name}! 👋`)
}
```