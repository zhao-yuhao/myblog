+++
title = "Linux 常用命令"

description = "记录Linux当中的常用命令，以备查看"

date = 2021-03-13T13:09:18+08:00
tags = ["research","linux"]

+++

1、修改文件名：

```bash
sudo mv old_name new_name
```

修改文件夹名：

```bash
sudo mv old_name/ new_name/
```

同时，mv命令还能够移动文件：

```bash
sudo mv filename new_directory/filename
```

2、搜索文件或文件夹的方法

用于程序名的搜索：

```bash
whereis filename
```

指定目录下遍历查找：

```bash
find /directory -name filename
```

find是在指定的目录下遍历查找，如果目录使用 / 则表示在所有目录下查找，find方式查找文件消耗资源比较大，速度也慢一点。

在Linux文件系统内查找：

```bash
locate filename
```

Linux会把系统内所有的文件都记录在一个数据库文件中，使用locate + 文件名的方法会在Linux系统维护的这个数据库中去查找目标，相比于find命令效率会更高。

但此数据库并非实时更新，可以使用：

```bash
updatedb
```

进行更新，以保证结果的正确性

使用如下命令查找可执行文件：

```bash
which executable_file
```



