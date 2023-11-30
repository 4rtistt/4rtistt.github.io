---
layout: post
title: "Introduction to template style"
categories: Setup
permalink: introduction
author: f4tu
meta: "Introduction to template style"
tags: template
---

This is the notes about markdown style.

#### Math
`Preview:`

When $$a \ne 0$$, there are two solutions to $$ax^2 + bx + c = 0$$ and they are:
<div align="center">
    $$x_1 = {-b + \sqrt{b^2-4ac} \over 2a}$$
    $$x_2 = {-b - \sqrt{b^2-4ac} \over 2a} \notag$$
</div>

`Markdown:`

```md
When $$a \ne 0$$, there are two solutions to $$ax^2 + bx + c = 0$$ and they are:
<div align="center">
    $$x_1 = {-b + \sqrt{b^2-4ac} \over 2a}$$
    $$x_2 = {-b - \sqrt{b^2-4ac} \over 2a} \notag$$
</div>
```

```mermaid
graph TB;
    A[Do you have a problem in your life?]
    B[Then don't worry]
    C[Can you do something about it?]
    A--no-->B;
    A--yes-->C;
    C--no-->B;
    C--yes-->B;
```