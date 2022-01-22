---
title: "Network Protocol"
date: 2022-01-23T00:19:33+08:00
draft: false
---

# socket
## create listen socket
```
socket = fd3
bind(fd3, 8090)
listen(fd3)
accept(fd3, -> fd5 -> clone( /blocking
    recv(fd5 /blocking
```