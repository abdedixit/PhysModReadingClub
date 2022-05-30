---
layout: default
title: How to push commits to the website repo
nav_order: 99
---

## Jekyll installation (one time)

Before we can make any changes, Jekyll needs to be installed. See instructions here:
[Jekyll installation](https://jekyllrb.com/docs/)

## Git workflow

### Git installation (one time)

If git is not installed, install it by following instructions here:
[Git installation](https://github.com/git-guides/install-git)

### Git repo setup (one time)

Typical commands for git repo setup are:

1. git init --> To initialise local repo 
2. git clone --> To clone from this repo to local repo

### Git commit and push (recurring)

Typical git commands to commit and push are:

1. git add --> To add changed files to local repo
2. git commit --> To commit changes to local repo
3. git push --> To push changes from local repo to github repo

### Git cheat sheet

Useful list of common github commands:
[Git cheat sheet](https://www.atlassian.com/git/tutorials/atlassian-git-cheatsheet)

## Jekyll local website hosting

Before committing changes, it is useful to host the website locally and ensure the changes made are rendered properly. To do this, from the website directory, execute:

```console
foo@bar <website-dir> % bundle exec jekyll serve
```

Changes would then be visible at the address [http://localhost:4000](http://localhost:4000)