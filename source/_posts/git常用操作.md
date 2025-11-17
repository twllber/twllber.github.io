---
title: git常用操作
date: 2025-11-01 14:15:17
tags: git
---

## 拉取远程仓库

``` bash
git pull --rebase
```

拉取并更新在分支顶部

## 新建分支

``` bash
git branch -b <分支名>
```

新建分支并立即切换过去

## clone嵌套仓库

在遇到嵌套的仓库时，可以用下面的命令来避免嵌套仓库无法clone的情况

``` bash
git clone --recurse-submodules <仓库URL>
```

如果已经克隆了嵌套的仓库，可以用下面的命令初始化并更新子模块

``` bash
git submodule update --init --recursive
```
