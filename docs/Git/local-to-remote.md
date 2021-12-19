---
layout: default    
title: Git Local >> Remote
nav_order: 2
parent: Git
permalink: /git/local-to-remote
---

## Local >> Remote

### Basic Git

Git is to **synchronise files** between local machine and remote repository. I was quite confused in the beginning but eventually got the logic after trying again and again. 

> * Origin >> Remote address (such as GitHub or Bitbucket) 
> * Local >> Local PC (Local)

### Basic command to get started     

```
git init
```
To **initialise** the repository in the folder. This will generate `.git` file which is a **hidden file**. 

```
echo "hello world" > test.txt
git add test.txt
```
First line is to create the file `test.txt`, then this file is added to `.git` for commit later.  
> * `git add` can also be used for directory: `git add [folder-name]`

```
git status
```
To **check** the status 

```
git commit test.txt
```
**Commit** the new file ready for push to the origin. 

```
git checkout -b [new-branch-name]
```
`-b` is to **create** a new branch, then you will be switched to the new branch. 

```
git checkout [existing-branch]
```
This is to **switch** between existing branches 

```
git branch
```
To **check** which branch are you on

```
git branch -D [local-branch-name]
```
To **delete** local branch

```
git push origin -d [remote-branch-address]
```
To **delete** branch remotely
> Note: in case the origin is not set, you may need to use the origin remote address.  

```
git fetch origin 
```
To first **fetch** what you have in the remote address