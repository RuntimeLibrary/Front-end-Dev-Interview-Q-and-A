# 前端开发面试题

> 相关链接
> - https://segmentfault.com/a/1190000000465431
> - http://www.w3cplus.com/css/interview-question-css.html

## HTML

### 1. `doctype`的作用？标准模式与兼容模式有什么区别？
### 2. `HTML5`为什么只需要写`<!doctype html>`？
### 3. `行内元素`有哪些？`块级元素`有哪些？`空元素`有哪些？
### 4. 页面导入样式时，使用`link`和`@import`有什么区别？
### 5. 浏览器的`内核`分别是什么？

- IE — Trident
- Mozilla — Gecko
- Chrome — Blink（WebKit 的分支）
- Opera — 原为 Presto，现为 Blink

### 6. 常见`兼容性`问题？

## CSS

### 1. 介绍一下 CSS 的`盒子模型`，什么是 CSS 的盒子模型？这里有哪些 CSS 属性？

- 盒子模型（box model）有两种，IE 盒子模型和标准 W3C 盒子模型。
- 盒子模型的范围包括，内容（content）、填充（padding）、边框（border）、边界（margin）。
- 二者的区别是，标准 W3C 盒子模型的 content 部分不包含其他部分，而 IE 盒子模型的 content 部分包含了 padding 和 border。

<p align="center">
<img src="https://upload.wikimedia.org/wikipedia/commons/b/bd/W3C_and_Internet_Explorer_box_models.png" alt="W3C and Internet Explorer box models">
</p>

## JavaScript

### 1. `eval()`是做什么的？

将一个 JavaScript 代码字符串求值成特定的对象（把对应的字符串解析成 JavaScript 代码并运行）。

应该避免使用`eval()`，不安全、非常耗性能（一次解析成 JavaScript 语句，一次执行语句）。

详见：https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/eval

## 其他
