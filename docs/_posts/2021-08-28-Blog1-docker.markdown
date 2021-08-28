---
layout: post
title:  "Blog 1 - Docker"
date:   2021-08-28 12:06:20 -0700
categories: docker blog 
---

# What is Docker?
Is a type of Virtualization. 
.....

# Some basic commands
```
# Pull image
docker pull <image name>

# Pull Ubuntu 16.04
docker pull ubuntu:16.04
```

Docker run with port mapping
` docker run -p 8080:80 ubuntu:16.04 /bin/bash`
This command maps local port 8080 to port 80 inside the container


Tag your docker image:
` docker run --name <name of container> -p 8080:80 ubuntu:16.04 /bin/bash`