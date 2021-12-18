---
title: 重学前端系列 - 开篇
catalog: true
date: 2021-11-27 12:34:17
subtitle: 重学前端系列,开篇
lang: cn
header-img: /img/header_img/lml_bg.jpg
tags:
- 重学前端系列
categories:
- 重学前端系列
---


首先我们从一个面试题开始。面试题如下：

当在浏览器中输入 Google.com 并且按下回车之后发生了什么？

日常使用我们会经常输入一个url 去访问一个网站，那么我们清楚其中的详细过程吗。域名到服务器是怎么解析的，我们又是如何与服务通信，最终又是如何将服务器中的数据渲染到页面，以及页面最终的呈现方式？



别急，我们下面通过一张图来了解一下这个过程。

![google](https://tva1.sinaimg.cn/large/008i3skNgy1gwdn6nrpgvj30hj0eh0t5.jpg)

首先我们默认这些过程都发生在浏览器中，这次我们不会详细分析浏览器的基本原理，后面我们会在系列文章之后开篇幅来详细说明。通过上图，我们很容易的看到，`google.com`输入之后，我们按下回车。浏览器显示解析URL，包含协议，路径，参数等。之后会进入一个缓存判断，包含DNS ，请求，以及静态资源的判断是否有缓存。当没有缓存时，会首先取解析DNS和获取MAC地址，之后会进行TCP三次握手，如果是HTTPS的话会进行HTTPS 握手的流程。最终都会返回数据，然后进行页面渲染，最终我们在浏览器中看到显示的样子。

![image-20211113174030359](https://tva1.sinaimg.cn/large/008i3skNgy1gwdnua73hxj31g00omt9q.jpg)



以上是最终过程，也是我们下面系列文章所讨论的主要切入点。

1. TCP 三次握手/TCP 四次挥手
2. HTTPS 链接
3. HTML 基础
4. CSS 与 HTML
5. Javascript 入门(包含事件循环详解)

当然我们讲完上面之后还是会切入框架层面，当然只讲常用主流，其他框架可以自行探索，包含下面的篇章

6. React 17 详解(包含实例)
7. React Hooks 详解(包含实例)
8. Vue2 入门(包含实例)
9. Vue3 Composition API 使用教程(包含实例)

框架结束之后，我会展开前端工程方面，包含如下篇章

10. Nodejs 入门 (什么是模块化，AMD/CommonJS/ESM?)

11. Typescript 入门

12. Eslint、 Prettier、Husky 代码规范三剑客

    

以上是规划中的篇章，如果顺利的话，可能会对上面做一些展开，写入深入前端系列。



<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="知识共享许可协议" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br />本作品采用<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">知识共享署名-非商业性使用-相同方式共享 4.0 国际许可协议</a>进行许可。

