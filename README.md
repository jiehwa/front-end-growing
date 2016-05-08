# front-end-growing
前端进阶指南
[前端开发面试题](https://github.com/jiehwa/My-blog/tree/master/Front-end-Developer-Questions)
## 初级
### 1.掌握基础的HTML语法，能分清各个标签的作用和使用场景
要求：
1.知道哪些是块级标签，哪些是行内标签。知道通过`display`属性来更改标签的作用，能分清楚`inline`，`inline-block`,`block`区别
#### 1.1 a标签（伪类标签）
* a标签最常用的作用是作为一个文本超链接，因为本身是行内标签。

```
<a href="#" ></a>
```

* a标签同时用于一整块的可点击区域，但是此时要将`display`属性改为`inline-block`或者`block`再将内容嵌入。
* `a:hover`的使用——实现折叠菜单：

#### 1.2 表单类标签


### 2.理解css盒子模型，学会常见布局
#### 2.1能描述出来盒子模型
#### 2.2利用`box-sizing`来改变浏览器的计算盒子模型的规则
#### 2.3能够利用盒子模型构造出常见网页布局

[css参考手册](http://css.doyoe.com/)

### 3.理解float浮动和position定位
#### 3.1 float
* 什么是浮动，左浮动和右浮动，怎么清除浮动，

#### 3.1 position
* `position`有哪些：absolute(绝对定位)，relative（相对定位），fixed(固定位置)
* 能说出上面三个定位的区别

### 4.熟悉了解css3的小技巧
* 4.1 一行文字超过某个长度使用省略号，两行文字省略号怎么处理
 [大众点评M站](http://m.dianping.com/)下面的商户列表项中的标题使用了一行超过显示省略号，详情介绍使用了`两行`超过显示省略号
* 4.2 圆形头像，设置边框圆角`border-radius`
* 4.3 利用css3`transfrom`属性对元素进行放大，旋转
例子：[大众点评M站](http://m.dianping.com/)头部城市名字右侧的倒下来的类似下拉按钮怎么实现