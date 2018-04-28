---
title: javascript-faq-0
date: 2018-04-13 22:38:56
tags: javascript
categories: javascript
---
1. gulp/grunt 与 webpack的区别是什么?


1. webpack是解决什么问题而生的?

1. webpack 如何配置多入口文件?

1. 如何提高webpack构建速度?

1. 利用webpack如何优化前端性能?

1. webpack的构建流程是什么?从读取配置到输出文件这个过程尽量说全.

1. javascript 中 this 是怎么工作的？
    * `this` 永远指向函数运行时所在的对象，不是函数创建时所在的对象
    * 匿名函数和不处于任何对象中的函数，指向 global 对象
    * `call, apply, bind` 中传递的 `this` 参数就是实际的指向对象
    * 普通函数调用时，函数被谁调用，`this` 就指向谁