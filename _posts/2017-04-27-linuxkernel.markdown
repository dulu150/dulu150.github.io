---
layout: post
title:  "LINUX内核实现的小知识点"
date:   2017-04-26 22:34:01 +0800
categories: jekyll update
---

# 1.C语言中函数的返回值通过EAX寄存器返回，所以FORK系统调用中，在汇编时候可以使用EAX判断函数是否返回成功。