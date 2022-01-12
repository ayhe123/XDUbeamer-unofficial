# XDUbeamer-unofficial

仿照西安电子科技大学PPT模板自制的beamer模板

## 使用方法

首先要确保 `XDUbeamer.sty` 宏包和 `img` 文件夹与你的 `.tex` 文件在同一目录下. 一个简单的例子是:

```latex
\documentclass{ctexbeamer}
\usepackage{XDUbeamer}

\title{在这里输入标题}
\subtitle{在这里输入副标题}
\institute{在这里输入学院}
\author{在这里输入名字}

\begin{document}
\begin{frame}[plain]
    \titlepage
\end{frame}
\begin{frame}
    ...
\end{frame}
\end{document}
```

需要注意的是, 标题页要加上 `[plain]`.

`XDUbeamer.sty` 宏包有一个参数: 主题颜色, 有 red, blue 两种选择. 比如在前面的例子中把 `\usepackage{XDUbeamer}` 换成 `\usepackage[blue]{XDUbeamer}` 就可以使用蓝色主题. 在不加参数的情况下默认采用红色主题.

其他的使用方法与 beamer 的类似.

## 参考资料

本项目的一部分内容参考了 [easymcm](https://github.com/xjtu-blacksmith/easymcm) 以及 [XDU实验报告、课程报告模板](https://levitate-qian.github.io/2020/12/01/latex-lecture/).
