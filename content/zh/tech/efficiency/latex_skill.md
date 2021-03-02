+++
title = "LaTeX--奇技淫巧"

description = "LaTeX 的一些技巧，科研记录"

date = 2021-02-06T14:47:18+08:00
tags = ["research","latex"]

+++

在日常的科研生活当中，我们需要经常接触LaTeX，LaTeX是一种排版语言，“所思即所得”，非常的方便。学习成本较低，掌握了必要的命令，借助于模板，能够非常快的上手，但对于一些技巧，有时候难以利用查到，因此需要记录下来以备未来查看。

1、如何插入图片，达到如下图的图文并排的效果？

![latex-phototext.png](/images/latex-phototext.png "LaTeX·图文并排")

```latex
\begin{wrapfigure}{r}{3.5cm}
\includegraphics[width=3.5cm]{figures/path.eps}
\caption{description.}\label{fig:example}
\end{wrapfigure} 
```

2、控制字体大小

```latex
\tiny
\scriptsize
\footnotesize
\small
\normalsize
\large
\Large
\LARGE
\huge
\Huge
```

