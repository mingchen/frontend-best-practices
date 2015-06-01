Web前端开发最佳实践
===================

**目录**

  * [Web前端开发最佳实践](#web%E5%89%8D%E7%AB%AF%E5%BC%80%E5%8F%91%E6%9C%80%E4%BD%B3%E5%AE%9E%E8%B7%B5)
    * [CSS](#css)
      * [使用<code>em</code>作为<code>font-size</code>的单位](#%E4%BD%BF%E7%94%A8em%E4%BD%9C%E4%B8%BAfont-size%E7%9A%84%E5%8D%95%E4%BD%8D)
      * [使用数字来指定颜色](#%E4%BD%BF%E7%94%A8%E6%95%B0%E5%AD%97%E6%9D%A5%E6%8C%87%E5%AE%9A%E9%A2%9C%E8%89%B2)
    * [参考](#%E5%8F%82%E8%80%83)


## CSS

### 使用`em`作为`font-size`的单位

CSS可以使用`px`, `pt`, `em`和百分比来定义字体大小`font-size`。 推荐的做饭`em`作为字体单位可以提供可缩放的字体。

> px像素（Pixel）是相对长度单位，像素px是相对于显示器屏幕分辨率而言的。
> em是相对长度单位，相对于当前对象内文本的字体尺寸。如当前对行内文本的字体尺寸未被人为设置，则相对于浏览器的默认字体尺寸。

`px`是绝对单位，IE无法正常的缩放px单位的字体。
`em`是相对单位，它会寄出父容器的字体大小。

    h3 { font-size: 1.2em }

各种字体单位自己的换算关系：

    1em == 12pt == 16px == 100%


### 使用数字来指定颜色

CSS 支持16种颜色名字的定义: aqua, black, blue, fuchsia, gray, green, lime, maroon, navy, olive, purple, red, silver,
teal, yellow, white。某些浏览器支持更多的颜色定义。为了保持浏览器的兼容性，使用数字来定义颜色。

    h1 { color: #E6F1F6 }




## 参考

* http://www.w3.org/WAI/GL/css2em.htm

