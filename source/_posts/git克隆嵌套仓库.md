---
title: git克隆嵌套仓库
date: 2025-11-01 14:15:17
tags: git
---
``` bash
git clone --recurse-submodules <仓库URL>
```

如果已经克隆了仓库，可以用下面的命令初始化并更新子模块

``` bash
git submodule update --init --recursive
```
