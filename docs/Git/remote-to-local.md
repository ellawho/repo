---
layout: default    
title: Git Remote >> Local
nav_order: 2
parent: Git
permalink: /git/remote-to-local
---

## Remote >> Local 

### Basic Git

Git is to **synchronise files** between local machine and remote repository. I was quite confused in the beginning but eventually got the logic after trying again and again. 

> * Origin >> Remote address (such as GitHub or Bitbucket) 
> * Local >> Local PC (Local)

### Basic command to get started    

```
git clone https://github.com/USER/REPO.git
```
Cloning repo in to PC folder

```
git fetch ssh://git@github.com:USER/REPO.git
```
Using SSH or HTTP
> * git fetch `https://github.com/USER/REPO.git`

```
git checkout FETCH_HEAD -- index.html
```
