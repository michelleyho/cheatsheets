---
title: "Git: Common Commands"
categories: TIL
author: "Michelle Ho"
meta: "quick_ref"
date: 2024-07-31
---

### Configuration
```
git config --global user.name <username>
git config -global user.email <useremail@email.com>
```

### Usual workflow
Setup
```
git init
```
Status
```
git status
```
Stage
```
git add .  # Add all
git add <filename> 
```
Commit 
```
git commit -m <message>  # for simple, on cmdline commit
git commit # brings to editor to add commit headline, and commit elaboration
```

### Cloning/Checkout
Clone
```
git clone <url link>
```
New Branch & Checkout 
```
git checkout -b <update-name> 
```
Branch
```
git branch # shows which branches are available
git checkout <branch name> # switch to branch
```
Push
```
git push <remote name> <branch name>
git push origin <branch name>
```
Pull
```
git pull
```
Show
```
git show
```




