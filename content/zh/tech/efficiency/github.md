+++
title = "Git使用技巧"

description = "Git在计算机科研人员当中具有非常重要的作用"

date = 2021-03-11T20:40:18+08:00
tags = ["research","github"]

+++

一直都不太会使用Git，但是对于一名计算机从业者来说，Git是非常重要的工具，因此利用近期需要整理代码的契机，下决心学会使用Git。

## 开始

首先应该学会如何创建Git仓库：

```bash
git init
```

上述命令会使得当前目录作为Git仓库，使用如下命令表示对filename进行追踪：

```bash
git add filnname
```

使用如下命令进行提交：

```bash
git commit -m 'description'
```

## 基本操作

![git-command.jpg](/images/git-command.jpg "Git·常用命令")