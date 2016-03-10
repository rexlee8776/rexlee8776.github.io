---
title: how to generate a development environment by docker?
layout: post
---

###install git
```
apt-get install -y git
git config --global user.name "Rex Lee"
git config --global user.email "rexlee8776@gmail.com"
git config --global core.editor vim
ssh-keygen
```
###submit image
```
docker commit rex rexlee8776/evilittle:dev_env
docker login
docker push rexlee8776/evilittle:dev_env
docker pull rexlee8776/evilittle:dev_env
```
