+++
title = "CUDA安装相关事宜"

description = "windows10安装CUDA与Visual Studio 2019"

date = 2021-06-28T14:49:18+08:00
tags = ["research","cuda", "parallelgramming"]

+++

## 自动补全与代码高亮

利用 Visual Studio 2019 写 CUDA 代码如何实现自动补全与代码高亮？只需添加以下头文件即可：

```c++
# include "cuda_runtime.h"
# include "device_launch_parameters.h"
```

