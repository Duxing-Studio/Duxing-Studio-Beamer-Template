# Duxing-Studio-Beamer-Template
笃行工作室Latex 演示模板

## 示例
```latex

\documentclass[presentation]{beamer}
\usepackage{ctex}

\usecolortheme{duxing}
\usefonttheme{duxing}
\useinnertheme{duxing}

\usepackage[utf8]{inputenc}
\usepackage[UKenglish]{babel}
\usepackage{booktabs}
\usepackage{caption}
\usepackage{subcaption}
\usepackage{graphicx}
\usepackage{amsmath}
\usepackage{amsfonts}
\usepackage{amssymb}

\title{标题}
\subtitle{副标题}
\author{作者}
\date{}
\institute{
  \includegraphics[height=0.7cm]{sysu_logo.png}
  \includegraphics[height=0.7cm]{duxing_logo.png}
}
\begin{document}

\frame{\titlepage}

\section{前言}

\begin{frame}
    \frametitle{页标题}
    内容
\end{frame}

\begin{frame}[standout]
    Questions
\end{frame}

\end{document}
```
