Web前端开发最佳实践
===================


CSS
---

使用`em`作为`font-size`的单位
+++++++++++++++++++++++++++++

`em`作为字体单位可以提供可缩放的字体。

    h3 { font-size: 1.2em }

各种字体单位自己的换算关系：

    1em == 12pt == 16px == 100%


使用数字来指定颜色
++++++++++++++++++

CSS 支持16种颜色名字的定义: aqua, black, blue, fuchsia, gray, green, lime, maroon, navy, olive, purple, red, silver,
teal, yellow, white。某些浏览器支持更多的颜色定义。为了保持浏览器的兼容性，使用数字来定义颜色。

    h1 { color: #E6F1F6 }




参考
----

* http://www.w3.org/WAI/GL/css2em.htm
