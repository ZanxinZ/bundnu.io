---
title: "About"
description: Hi I'm Zanxinz
date: 2021-10-17T00:29:51+08:00
draft: false
---


## Hugo-theme-stack

### 如何使用 hugo

hugo 是一个程序，在命令行里直接运行，通常是 [hugo + 指令] 的形式来执行某些功能。

例如，新建一个 index.md

```c

hugo new index.md

```

**想要文档正常显示，记得把 draft 设置为 false**

### 如何设置文件夹结构

左侧的菜单栏设置如下，其中 `/` 代表点击主页时候，会跳至 `/`。

![menu](about/menu.jpg)

content 之下可以添加 index.md 作为网站 `/` 访问到的内容。

![index.md](about/indexmd.jpg)

在 content 之下可以添加子目录，用于分类。如下图的添加了 code 目录，并且在子目录下添加了 _index.md 用以显示进入 code 时显示的内容

_index.md 只是用于显示当前页面的标题信息，不用来书写主要内容
![_index](about/_indexUse.jpg)

- 输入指令以新建文件
    > hugo new code/_index.md

#### 多个文件链接

-
