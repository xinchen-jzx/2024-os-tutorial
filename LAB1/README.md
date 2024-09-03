# Lab1: Unix Utilities

## 前言

本实验需要编写一些用户程序，执行系统调用来达成目标。作为第一个实验，本次实验内容比较简单，主要内容是展示用户如何调用操作系统的接口，即system call，在下一个实验中将详细展示系统调用的工作流程。

本次实验的学习目标是：
- 学习并理解用户使用shell执行命令时的具体过程；
    - 命令行传入的参数如何被进程解析并使用？
- 对Unix的进程间通信方式之一pipe有一定的了解；
- 了解Unix中的file description，理解Unix中“一切皆文件”的理念；
- 初步了解make项目以及Makefile。

## 前置工作

进入工作文件夹，输入以下命来：
```bash
git checkout lab1_utils     # 切换到lab1_utils分支，对应本实验
git clean -xfd              # 清除无关文件（未追踪的、忽略的文件和文件夹）
git checkout -b solve_lab1  # 新建一个solve_lab1分支，来记录自己的编程过程
```