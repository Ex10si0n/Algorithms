---
description: Introduction
---

# The Algorithms Interest Group

![](.gitbook/assets/what-is-an-algorithm-featured.png)

## Introduction

Lecturer: Steve Yan [![](https://img.shields.io/badge/Web-aspires.cc-blue)](https://www.aspires.cc)

Location: Macao Polytechnic Institute

Time Schedule: TBA

### Useful URLs

Typora: [typora.io](https://typora.io) ![](https://img.shields.io/badge/Web-.md-red)

LeetCode: [leetcode/problemset](https://leetcode.com/problemset/all/) ![](https://img.shields.io/badge/Web-OJ-blue)

POJ: [poj/problemlist](http://poj.org/problemlist) ![](https://img.shields.io/badge/Web-OJ-blue)

### How to use this repository?

Clone via HTTPS using following command or Click `Code` then `Download ZIP`.

```bash
git clone https://github.com/Ex10si0n/Algorithms.git
```

You can open `README.md` (Markdown File: open via [Typora](https://typora.io) or notepad.exe) locally or on [this](https://github.com/Ex10si0n/Algorithms) page.

### Assessments

* Attandance
* Assignments

### ~~Outline (Legacy Version for 2021)~~

~~This lecture will specifically focus on the Algorithm implementation. My example code will be demonstrated in Python, but you can adopt any kind of programming language if you prefer.~~

~~No slides are distributed (cuz. I do not regard slides as an efficient format to display codes) but all of the codes and explanations are shown on this `README.md`.~~

### Outline (New Version for 2022)

C++ is essential for Algorithms Development due to its high efficiency of execution. However, it is not as easy as the Python language in implementation. In this Interest Group, we adopted C++ in Algorithm design. You are welcome to set this website as a favorite to visit at any time. No slides will be distributed in this lecture, you are free to copy or share the codes on this website. All the contents are under the[ Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/) license.

**The following topics will be covered in the Interest Group**

* **Fundamental Methodologies**
  * [Greedy (贪心)](Ch1-Fundamental.md#greedy)
  * [Binary Search (二分)](Ch1-Fundamental.md#binary-search)
  * [**Recursion (递归)**](Ch1-Fundamental.md#recursion)****
  * [Data Structure (数据结构)](Ch1-Fundamental.md#data-structure)
    * Linear Structure
      * [Queue (队列)](Ch1-Fundamental.md#queue)
      * [Stack (栈)](Ch1-Fundamental.md#stack)
    * Generic Tree
      * [Tree (树)](Ch1-Fundamental.md#tree)
      * [Binary Tree (二叉树)](Ch1-Fundamental.md#binary-tree)
      * Linear Structure (maintained by Tree) (由树维护的线性结构)
        * [Binary Indexed Tree (二叉索引树)](Ch1-Fundamental.md#binary-indexed-tree)
        * [Segment Tree (线段树)](Ch1-Fundamental.md#segment-tree)
    * Generic Graph
      * [Graph (图)](Ch1-Fundamental.md#graph)
* **Graph Theory (图论)**
  * [Minimum Spanning Tree (最小生成树)](Ch2-Graph-Theory.md#minimum-spanning-tree)
  * ****[**Depth-first Search (深度优先搜索)**](Ch2-Graph-Theory.md#depth-first-search)****
  * Multiple Source Shortest Path - I (多源最短路径)
    * [Floyed-Warshall](Ch2-Graph-Theory.md#floyed-warshall)
  * ****[**Breadth-first Search (广度优先搜索)**](Ch2-Graph-Theory.md#breadth-first-search)****
  * Shortest Path - II (单源最短路径)
    * [Dijkstra](Ch2-Graph-Theory.md#dijkstra)
    * [SPFA](Ch2-Graph-Theory.md#spfa)
  * Network Flow (网络流)
    * [Ford-Fulkerson (最大流算法)](./#ford-fulkerson)
  * Bipartite Graph (二分图)

## Before We Start (for MPI Algorithms lecture)

Here are some useful tools for coding. I will briefly introduce them as follows:

### vim (neovim)

Vim is a highly efficient code editor in the command line. I will use **vim** to implement the code of algorithms in this lecture. You can try to use it with ease because I will specifically introduce some shortcuts and modes of vim. But you are free to adopt any IDEs or text editor you like. You can install it by command:

#### Installation

```bash
# Linux
sudo <package-manager> install neovim

# macOS
brew install neovim

# Windows
choco install vim
```

#### Package manager installation on macOS and Windows

```bash
# macOS (in Terminal.app)
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

# Windows (in powershell.exe with Administrator)
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
```

#### Or install vim in IDEs (better experience)

Demo at [Jetbrains/using-product-as-the-vim-editor](https://www.jetbrains.com/help/pycharm/using-product-as-the-vim-editor.html)

### LeetCode

![](../assets/logo-dark.e99485d9b.svg)

LeetCode in [知乎](https://www.zhihu.com/topic/19925162/hot). It is a good platform for elementary algorithms learning. It is appropriate for preparing for a job as well as learning algorithms.

If you do not have a LeetCode account, please visit [Leetcode.com](https://www.leetcode.com) or [Leetcode-cn.com (中文题目)](https://leetcode-cn.com) to create an account.
