---
layout:     post
title:      HTTP和静态Web服务器
subtitle:   搭建Python自带静态Web服务器
date:       2021-02-16
author:     BB
header-img: img/pythonPro.jpg
catalog: true
tags:
    - python
    - HTTP
    - Web
---


搭建Python自带静态Web服务器
===========================

**学习目标**

-   能够知道搭建Python自带Web服务器

* * * * *

### 1. 静态Web服务器是什么？ 

可以**为发出请求的浏览器提供静态文档的程序**。

平时我们浏览百度新闻数据的时候，**每天的新闻数据都会发生变化，那访问的这个页面就是动态的**，而我们开发的是**静态的，页面的数据不会发生变化**。

### 2. 如何搭建Python自带的静态Web服务器 

搭建Python自带的静态Web服务器使用 **python3 -m http.server 端口号**,
效果图如下:

![搭建web服务器](https://www.hualigs.cn/image/60b60f99bcaf6.jpg)

**-m选项说明:**

-m表示**运行包里面的模块**，执行这个命令的时候，需要进入你**自己指定静态文件的目录**，然后通过浏览器就能访问对应的
html文件了，这样一个静态的web服务器就搭建好了。

### 3. 访问搭建的静态Web服务器 

通过浏览器访问搭建的静态Web服务器，效果图如下:

![搭建web服务器](https://www.hualigs.cn/image/60b60f99bcaf6.jpg)

### 4. 查看浏览器和搭建的静态Web服务器的通信过程 

查看http的通信过程,效果图如下:

![搭建web服务器](https://www.hualigs.cn/image/60b60f99e6c0f.jpg)

### 5. 小结 

-   静态Web服务器是为发出请求的浏览器提供静态文档的程序，
-   搭建Python自带的Web服务器使用python3 –m http.server 端口号
    这个命令即可，端口号不指定默认是8000

