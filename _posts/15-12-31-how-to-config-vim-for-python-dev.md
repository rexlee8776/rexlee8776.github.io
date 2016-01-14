---
layout: post  
title: how to config vim for python dev env
categories: [blog ]  
tags: [python, vim ]  
description: 
---
>this article introduce how to config vim for a python development environmen

## package autoload tool
**install pathogen.vim**
```shell
mkdir -p ~/.vim/autoload ~/.vim/bundle && \
curl -LSso ~/.vim/autoload/pathogen.vim https://tpo.pe/pathogen.vim
```
or
```shell
git clone https://github.com/rkulla/pydiction.git
```

## plugins

### taglist
```shell
apt-get install vim-scripts
vim-addons install taglist
```

### pydiction
```shell
git clone https://github.com/rkulla/pydiction.git
```

### NERDTree
```shell
git clone https://github.com/scrooloose/nerdtree.git
```

### AutoComplPop
**install**

1. download dependent plugin l9.vim
    http://www.vim.org/scripts/script.php?script_id=3252
2. download acp and install
    http://www.vim.org/scripts/script.php?script_id=1879 
    
