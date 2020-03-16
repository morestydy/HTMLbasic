[toc]
 <center> <font size=5> HTML学习 </font> </center>

[菜鸟教程]{https://www.runoob.com}

`XML`:`extension markup language`,用于定义文档结构

# 实例解析
`<!DOCTYPE html>`: 声明为`HTML5`文档<br>
`<html>`元素是`HTML`页面的根元素<br>
`<head>`元素包含了文档的元`(meta)`数据,如`<meta charset="utf-8"`<br>
`<body>`元素包含可见的页面内容<br>
`<h1>`元素定义了一个大标题<br>
`<p>`元素定义了一个段落
## `HTML`标签
<font size=4> <标签>内容</标签> </font> <br>
+ HTML通常是成对出现的,`<b>`和`</b>`
+ HTML标签是由尖括号包围的关键词,`<html>`
## HTML网页结构


## 组成
### <!DOCTYPE>声明
`<!DOCTYPE>`声明浏览器正确显示网页
1. 标题, 通过`<h1>-<h6>`标签来定义
2. 段落, 通过`<p>`来定义的
3. 连接,通过`<a>`来定义`<a href="https://www.runoob.com">这是一个链接</a>`
4. 图像,通过`<img>`定义,`<img src="/user.png" width="258" height="39"/>`
## HTML 元素
|开始标签|元素内容|结束标签|
|---|---|---|
|`<p>`|这是一个段落|`</p>`|
|`<a href="default.html">`|这是一个链接|`</a>`|
|`<br>`|换行||

一些标签的使用,要所有的标签要闭合,不管是单体标签还是成对标签.
### 属性http://www.runoob.com
+ `HTMl`元素可在元素中添加 **附加信息** 
+ 属性一般描述于 **开始标签**
+ 属性总是成对以名称/值对的形式出现,**`比如: name="value"`**
#### 属性实例
`<a href="http://www.runoob.com">这是一个连接</a>`
HTML链接由`<a>`标签定义,链接地址在**href属性**中指定<br>
- [ ]  在某些个别情况下,比如属性本身就含有双引号,那么必须使用单引号: `name='John"ShotGun"Nelson'`
#### 部分元素属性
|属性|描述|
|---|---|
|class|为html元素定义一个或多个类名(classname)|
|id|定义元素的唯一id|
|style|规定元素的行内样式|
|title|描述了元素的额外信息(作为工具条使用)|
<a href="https://www.runoob.com">菜鸟教程</a>
+ [ ] `calss` 属性可以多用`class=" "`,而`id`属性只能单独设置`id=" "`,只能填写一个,多个无效
