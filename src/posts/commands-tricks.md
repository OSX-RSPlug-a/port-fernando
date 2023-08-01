---
title: Commands lines tricks
description: Some tricks commands.
date: '2023-4-26'
categories:
  - Commands lines
  - shell commands
published: true
---

![Svelte](pexels-pixabay-207580.jpg)

## Topics

- Shell
- Bash commands

Here are some tiny but useful OS with Linux 
commands, terminal tricks and shortcuts that 
will save you a lot of time while working with 
servers command line.


- List the past commands wrote in terminal, but 
 history less will show a short list of that; 
 To get out list, before the end of list press q;
```bash
 history | less
```

- Show the list of disk usage by folders in 
actual directory;
```bash
 du -d 1 -h 
```

- List the files in current directory, plus 
hidden files;
```bash
 ls -a 
```

- Compress all files on folder in tar;
```bash
 tar -czvf logs_archive.tar.gz *
```

- Show the ip routes on machine;
```bash
 route -n 
```

- Search a process open ports in expexific ip;
```bash
 nmap 127.0.0.1	
```

- Search a process with the name associate;
```bash
 ps aux | grep java
```

- Run a command in background generating a kind 
of a log of error and output;
```bash
 nohup yarn dev:server </dev/null >nohup.out 2>nohup.err & 
```

- Show the log or a file restricted by the number 
of lines u wish to see;
```bash
 tail -200f lynis.log 
```

- Show socket and TCP statistics. It allows showing 
information similar to netstat;
```bash
 ss -turlp
```     

- Commando for remote and local file-copying tool with 
.pem key- It's not a good practice, but sometimes in 
a emergency;
```bash
 rsync -Pav "ssh -i ./posgres-replica-111111.pem" -ac ${PGDATA}/ hostname@11.111.11.1:/srv/pgsql/standby/ --exclude postmaster.pid
```  

- To access ssh by .pem key - It's not a good practice,
 but sometimes in a emergency ;
```bash
 ssh -i folder/stack.pem hostname@11.111.11.11 
```  

- Show how much memory the system in use in megabytes;
```bash
 free -m 
```  

- Clear the cached memory- you can do with 1, 2 and 4 too;
```bash
 sysctl -w vm.drop_caches=3  
```  

- Show ipTables rules in the machine;
```bash
 sudo iptables -L
```  

```ts
function greet(name: string) {
	console.log(`Hey ${name}! 👋`)
}
```
