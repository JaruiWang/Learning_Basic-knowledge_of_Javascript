# JavaScript的组成
JavaScript包括ECMAScript，DOM和BOM三部分。
ECMAScript就是JS基础，学习JS的基础语法；
JSAPI学习的DOM和BOM。

1. ECMAScript
ECMAScript是由ECMA国际（原欧洲计算机制造商协会）进行标准化的一门语言。
ECMAScript：ECMAScript规定了JS的编程语法和基础核心知识，是所有浏览器厂商共同遵循的一套JS语法工业标准。

2. DOM——文档对象模型

文档对象模型（Docunment Object Model，简称DOM）
是W3C组织推荐的处理可扩展标记语言的标准编程接口。
通过DOM提供的接口可以对页面上的各种元素进行操作（大小，位置，颜色等）。

3. BOM —— 浏览器对象模型

BOM(Browser Object Model，简称BOM)是指浏览器对象模型，它提供了独立于内容的，可以与浏览器窗口进行互动的对象结构。通过BOM可以操作浏览器窗口，比如弹出框，控制浏览器跳转，获取分辨率等。


## JS的3种写法

### 1.行内式JS
可以将单行或少量JS代码写在HTML标签的事件属性中（以on开头的属性），如onclick。
```HTML
<input type="button" value="唐伯虎" onclick="alert('秋香姐')">
```
- 注意单双引号的使用：在HTML中推荐使用双引号，JS中我们推荐使用单引号。

- 可读性差，在HTML中编写JS大量的代码时，不方便阅读；

- 引号易错，引号多层嵌套时，比较容易弄混；

- 特殊情况下使用。


### 2.内嵌式JS
可以将多行JS代码写到<script>标签中

内嵌式JS是学习时常用的方式

```JS
<script>
    alert("沙漠骆驼");
</script>
```

### 3.外部JS文件
JS文件写在外部，然后再在HTML文件中引用
```HTML
 <script src="my.js"></script>

```

