<center><span style="color:inherit;background:背景颜色;font-size:3em;font-family:字体;"><b>Typora 使用教程</b></span></center>

<center><b>柳思明</b> &nbsp &copy; 2020</center>



## 1.Typora是什么？

### 1.1 Typora是什么？

Typora是一款Markdown编辑器。

### 1.2 Markdown是什么？

Markdown是一种轻量级标记语言，创始人是约翰·格鲁伯（John Gruber）。它允许人们使用易读易写的纯文本格式编写文档，然后转换成有效的XHTML（或者HTML）文档。由于Markdown的轻量化、易读易写特性，并且对于图片，图表、数学式都有支持，目前许多网站都广泛使用Markdown来撰写帮助文档或是用于论坛上发表消息。 

所谓：阴阳相生。有轻就有重，有轻量级标记语言，就会“重量级”标记语言。Word就是一款大家熟知的“重量级”标记语言编辑器，专有名词是富文本编辑器。在Markdown编辑器被发明之前，大家都是在使用富文本编辑器。Typora是一款Markdown编辑器，Word是一款富文本编辑器，二者的区别到底是什么呢？我们之前使用富文本编辑器，非常好用啊，为什么还需要Markdown呢？这是学习Markdown的人都会遇到的问题，现以Typora和Word为例，说说Markdown编辑器和富文本编辑器的区别：

**<font color='green'>Markdown编辑器（Typora）和富文本编辑器（Word）</font>**

1. **功能：Typora ≈ < Word**

由于我们熟悉Word，对Typora了解不多，数量掌握，所以感觉上Word功能强大，其实，数量掌握Typora，能实现的功能并不比Word少。

2. **使用难度：Typora>Word**

Word一般通过点击、右键等操作即可使用，而Typora则需要额外掌握一套标记语言，使用难度方面Typora要难于Word。

3. **使用投入度：Typora>Word**

使用Word的时候，需要频繁地点击工具栏，就会影响写作的投入度；而使用Typora，基本上通过文本的输入就能实现写作和排版。

4. **兼容性：Typora>Word**

对于互联网写作的人来说，这一点十分重要。

Word文档用其他软件打开经常出现乱码，而Markdown本身就有文本写成，是一套完整的标记语言，在各支持Markdown的网站之间交流方便，兼容性强，即使是用非Markdown编辑器打开，也不会出现明显的乱码。

5. **直观性：Typora>Word**

在直观性方面，Typora在Markdown编辑器中已经是佼佼者了，当然和Word相比，直观性仍然会稍逊一筹。

6. **总结：**

* Typora等Markdown编辑器适用于互联网写作，而Word等富文本编辑器适用于工作等非互联网场景；
* Markdown编辑器适用于具有一定互联网技术的人群，富文本编辑器更适用于普通大众；
* 正是因为有一定的门槛，从使用人数来说，富文本编辑器的使用人数更多，但使用人数多并不代表一定好，比如，使用安卓系统手机的人比使用苹果IOS手机的人多，但并不代表安卓系统手机就更好。二者并没有高下之分，只是擅长的领域、适应人群不同而已。但有一点需要说明的是，对于已掌握Typora的人来说，就一定会喜欢上Typora；就像使用过iPhone的人，很难再返回使用安卓手机一样。

### 1.3 HTML是什么？

HTML（英文全称是Hyper Text Markup Language，中文全称是超文本标记语言）是一种标记性语言。所谓超文本，顾名思义就是除了文字，还可以包含图形、动画、声音、链接等非文字元素。

本质上，HTML和我们日常交流的语言没有什么区别，不同点在于：自然语言是人与人之间交流的语言，而HTML是人与浏览器之间交流的语言。也就是说，通过HTML命令告诉浏览器，在网页的哪个位置，放置什么控件，而控件长啥样，具体有什么功能，则分别需要CSS和Javascript来实现。

### 1.4 CSS是什么？

CSS（英文全称：Cascading Style Sheets，中文全称：层叠样式表）是一种用来表现[HTML](https://baike.baidu.com/item/HTML)或[XML](https://baike.baidu.com/item/XML)等文件样式的计算机语言。CSS 能够对网页中元素位置的排版进行像素级精确控制，支持几乎所有的字体字号样式，拥有对网页对象和模型样式编辑的能力。

JavaScript（简称：JS）是一种直译式高级脚本语言，常用来为网页添加各式各样的复杂动态功能，为用户提供更流畅美观的浏览效果。通常JavaScript脚本是通过嵌入在HTML中来实现自身的功能的。

### 1.5 相互关系

简单梳理下以上几者的关系：

1. Typora是一款Markdown编辑器。

2. Markdown和HTML都是标记语言，不同点在于，Markdown是文本语言，HTML除了文字，还可以包含图形、动画、声音、链接等非文字元素。

3. Markdown适用于互联网写作，HTML则不能直接用于写作，Markdown通过CSS可以转化为HTML。我们所看到的各种Markdown编辑器显示的样式都是转换为HTML后加上CSS显示的。

4. HTML加上CSS、Javascript呈现出我们最终看到的网页。

## 2. 为什么要使用Typora?

### 2.1 所见即所得

关于这一点，没有对比就没有伤害，大家看下面的两张图：第一张是印象笔记，第二张是Typora。这一点是将Typora从其他Markdown编辑器中挑选出来的主要原因。

![image-20200916123318251](D:\Program Files\Typora\文件存档\Typora使用教程\Typora使用教程.assets\image01.png)

![image-20200916123805441](D:\Program Files\Typora\文件存档\Typora使用教程\Typora使用教程.assets\image02.png)

### 2.2 网站兼容性强

这一点是将Typora从与其他Word之类的富文本编辑器中脱颖而出的主要原因。正因为以上两点，让Typora称为互联网写作的首选。

### 2.3 美观

从官方网站到软件操作界面都非常漂亮，我第一次登陆Typora官网主页是就被首页的动图深深吸引。之前在印象笔记也使用过Markdown，但也就是因为那么充满代码的乌漆嘛黑的界面，再加上需要学习一套标记语言，真是让人“没有开始，就结束了。”

### 2.4 私人订制

这一点个人超喜欢，大家看我现在使用的主题，就是我自己根据自己的喜好“私人订制”的。

### 2.5 免费

哈哈！其实这个软件如果收费我也会购买，何况无论是公司还是个人，都可以免费使用。

## 3. 怎么使用Typora？

### 3.1 Typora界面介绍

#### ![image-20200916125135955](D:\Program Files\Typora\文件存档\Typora使用教程\Typora使用教程.assets\image03.png)

### 3.2 常用快捷键/语法

| 功能               | 快捷键/语法                                                  |          效果          |
| :----------------- | :----------------------------------------------------------- | :--------------------: |
| 加粗               | <kbd>Ctrl</kbd>+B 或者 `**加粗**` 或者 `__加粗__`            |        **加粗**        |
| 斜体               | <kbd>Ctrl</kbd>+I 或者 `*斜体*` 或者 `_斜体_`                |         *斜体*         |
| 加粗且斜体         | `***加粗且斜体***` 或者 `___加粗且斜体___`                   |    ***加粗且斜体***    |
| 下划线             | <kbd>Ctrl</kbd>+U 或者 `<u>下划线</u>`                       |     <u>下划线</u>      |
| 删除线             | <kbd>Alt</kbd>+<kbd>Shift</kbd>+5 或者 `~~删除线~~`          |       ~~删除线~~       |
| 水平分割线         | `***` 或者 `- - -` 或者 `_ _ _`                              |           —            |
| 高亮               | `==高亮==`                                                   |        ==高亮==        |
| 下标               | `~下标~`                                                     |        下标~2~         |
| 上标               | `^上标^`                                                     |        上标^2^         |
| 注释               | `[^注释1]`                                                   |      注释[^注释1]      |
| 代码               | <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+` 或者 ``                   |         `代码`         |
| 选中一行           | <kbd>Ctrl</kbd>+L                                            |           /            |
| 选中一个单词       | <kbd>Ctrl</kbd>+D                                            |           /            |
| 选中相同格式的文字 | <kbd>Ctrl</kbd>+E                                            |           /            |
| 生成目录           | `[TOC]`                                                      |           /            |
| 一级标题           | <kbd>Ctrl</kbd>+1 或者 #+空格+文字                           |           /            |
| 二级标题           | <kbd>Ctrl</kbd>+2 或者 ##+空格+文字                          |           /            |
| 三级标题           | <kbd>Ctrl</kbd>+3 或者 ###+空格+文字                         |           /            |
| 四级标题           | <kbd>Ctrl</kbd>+4 或者 ####+空格+文字                        |           /            |
| 五级标题           | <kbd>Ctrl</kbd>+5 或者 #####+空格+文字                       |           /            |
| 六级标题           | <kbd>Ctrl</kbd>+6 或者 ######+空格+文字                      |           /            |
| 返回顶部           | <kbd>Ctrl</kbd>+<kbd>Home</kbd>                              |           /            |
| 返回底部           | <kbd>Ctrl</kbd>+<kbd>End</kbd>                               |           /            |
| 创建表格           | <kbd>Ctrl</kbd>+T                                            |           /            |
| 创建超链接         | <kbd>Ctrl</kbd>+K 或者 `[链接名称](链接地址)`                | [百度](www.baidu.com)  |
| 搜索并替换         | <kbd>Ctrl</kbd>+H                                            |           /            |
| 插入图片           | <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+I 或者 复制粘贴 或者 直接拖动 <br>或者`![图片的替代文字](图片地址)` |           /            |
| 表情               | `:happy:` 或者 ​`:smiley:` 或者 `:cry:`​                       | :smiley: :happy: :cry: |
| 向右缩进           | <kbd>Tab</kbd>                                               |           /            |
| 向左缩进           | <kbd>Shift</kbd>+<kbd>Tab</kbd>                              |           /            |
| 引言               | <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+Q 或者 >+空格               |           /            |
| 有序列表           | <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+[ 或者 *+空格               |           /            |
| 无序列表           | <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+] 或者 *+空格               |           /            |

备注：emoji表情符号链接地址：https://bj.96weixin.com/tools/emoji

### 3.3 高级技巧

#### 3.3.1 修改Typora主题

##### a.什么是Typora主题？

Typora主题位于Typora操作界面左上角的**<font color='green'>主题</font>**工具栏，在下拉框中可以看到Typora主题，选择对应的主题，会赋予基础文本不同的样式。

![image-20200915204608728](D:\Program Files\Typora\文件存档\Typora使用教程\Typora使用教程.assets\image03.png)

##### b.什么是CSS文件？

> 百度百科：层叠样式表（英文简称：CSS，全称：Cascad ing Style Sheets)是一种用来表现HTML（标准通用标记语言的一个应用）或XML（标准通用标记语言的一个子集）等文件样式的计算机语言。CSS不仅可以静态地修饰网页，还可以配合各种脚本语言动态地对网页各元素进行格式化。

打个比方，基础文本就像素描，CSS就像上色，上色之前整副画是黑白色的素描画，上色之后是颜色丰富的色彩画。

![上色-3](D:\Program Files\Typora\文件存档\Typora使用教程\Typora使用教程.assets\image05-上色.jpg)



##### c.打开CSS文件

由于一个Typora主题本质上就是一个CSS文件，因此，修改Typora主题就是修改CSS文件。

打开CSS文件的步骤是：**<font color='green'>文件</font>** > **<font color='green'>偏好设置</font>** > **<font color='green'>外观</font>** > **<font color='green'>打开主题文件夹</font>**

![image06](D:\Program Files\Typora\文件存档\Typora使用教程\Typora使用教程.assets\image06.png)

在点击**<font color='green'>打开主题文件夹</font>**后会看到一个名字为“themes”的文件夹后，在此文件夹下可以看到6个主题文件夹和相应的文件后缀名为.css的文件，分别是 github，media，newsprint，night，old-themes，pixyll。

![image06-themes](D:\Program Files\Typora\文件存档\Typora使用教程\Typora使用教程.assets\image06-themes.jpg)

后缀名为.css的文件就是CSS文件。选中某一个CSS文件，点击打开即可直接编辑。

![修改CSS文件-1](D:\Program Files\Typora\文件存档\Typora使用教程\Typora使用教程.assets\image07-修改CSS文件.jpg)

CSS文件可以直接通过软件<font color='green'>**记事本**</font>打开，也可以通过CSS编辑器打开，我使用的CSS编辑器是**<font color='green'>Visual Studio Code</font>**。

![image08](D:\Program Files\Typora\文件存档\Typora使用教程\Typora使用教程.assets\image08.png)

##### d.修改CSS代码

将**<font color='green'>Typora</font>**、<font color='green'>**Visual Studio Code**</font>同时打开，各占一半显示器屏幕，在<font color='green'>**VSCode**</font>调整好文件后保存，在<font color='green'>**Typora**</font>界面即可查看效果。（对于部分调整无法即时看到效果，重启<font color='green'>**Typora**</font>即可。）现以Github主题为例来说明如何修改CSS文件。

###### ==字体==

font-family：字体类型，用于某个元素的字体族名称或/及类族名称的一个优先表。

> 如font-family: Arial,Helvetica,sans-serif，这三种都是字体。如果系统有Arial这种字体，就显示Arial这种字体。如果系统没有Arial这种字体，就以Helvetica这种字体显示。以此类推。如果都没有。就以系统默认字体显示。

font-style：字体样式

> normal, italic, oblique：正常，斜体字，倾斜的文字

font-size：字体大小

> large, medium, small

font-weight：字体粗细

> normal, bold, bolder, lighter, 900

scr：字体文件来源 



###### ==Root==

root里定义的是界面颜色、文字颜色等

> text-color：文字颜色
>
> bg-color：背景颜色
>
> code-block-bg-color：代码块颜色
>
> side-bar-bg-color：文件夹、大纲处的颜色
>
> window-border：窗口边界颜色

* ```css
    :root {
      --side-bar-bg-color: #fafafa;
      --control-text-color: rgb(119, 119, 119);
    }
  ```



###### ==目录==

```css
.md-toc { 
    margin-top:20px;
    padding-bottom:20px;
}

a {
	color: #008000;
}
```

输出结果：

[toc]

###### ==代码块==

```css
/*代码块左边数字列*/
.CodeMirror-lines {
    padding-left: 4px;
}

/*代码工具栏：输入代码语言类型*/
.code-tooltip {
    box-shadow: 0 1px 1px 0 rgba(0,28,36,.3);
    border-top: 1px solid #eef2f2;
}

.md-fences,
code,
tt {
    border: 1px solid #e7eaed;
    background-color: #f8f8f8;
    border-radius: 3px;
    padding: 0;
    padding: 2px 4px 0px 4px;
    font-size: 0.9em;
}

/*代码*/
code {
    background-color: #f3f4f4;
    padding: 0 2px 0 2px;
}

/*代码块*/
.md-fences {
    margin-bottom: 15px;
    margin-top: 15px;
    padding-top: 8px;
    padding-bottom: 6px;
}


.md-task-list-item > input {
  margin-left: -1.3em;
}
```



###### ==标题==

```css
/*标题的位置、边距等设置*/
h1,
h2,
h3,
h4,
h5,
h6 {
    position: relative;
    margin-top: 1rem;
    margin-bottom: 1rem;
    font-weight: bold;
    line-height: 1.4;
    cursor: text;
}
h1:hover a.anchor,
h2:hover a.anchor,
h3:hover a.anchor,
h4:hover a.anchor,
h5:hover a.anchor,
h6:hover a.anchor {
    text-decoration: none;
}


h1 tt,
h1 code {
    font-size: inherit;
}
h2 tt,
h2 code {
    font-size: inherit;
}
h3 tt,
h3 code {
    font-size: inherit;
}
h4 tt,
h4 code {
    font-size: inherit;
}
h5 tt,
h5 code {
    font-size: inherit;
}
h6 tt,
h6 code {
    font-size: inherit;
}


/*标题的字体等设置*/
h1 {
    padding-bottom: .3em;
    font-size: 2.25em;
    line-height: 1.2;
    border-bottom: 1px solid #eee;
}
h2 {
    padding-top: .2em;
    padding-bottom: .2em;
    font-size: 1.75em;
    line-height: 1.225;
    border-bottom: 1px solid #eee;
}
h3 {
    font-size: 1.5em;
    line-height: 1.43;
}
h4 {
    font-size: 1.25em;
}
h5 {
    font-size: 1em;
}
h6 {
   font-size: 1em;
    color: #777;
}
```



###### ==表格==

```css
table {
    padding: 0;
    word-break: initial;
}
table tr {
    border-top: 1px solid #dfe2e5;
    margin: 0;
    padding: 0;
}
table tr:nth-child(2n) {
    background-color: #f8f8f8;
}

/*表头背景颜色、字体颜色*/
thead {
    background-color: #008000;
    color: #ffffff

}


table tr th {
    font-weight: bold;
    border: 1px solid #dfe2e5;
    border-bottom: 0;
    text-align: left;
    margin: 0;
    padding: 6px 13px;
}
table tr td {
    border: 1px solid #dfe2e5;
    text-align: left;
    margin: 0;
    padding: 6px 13px;
}
table tr th:first-child,
table tr td:first-child {
    margin-top: 0;
}
table tr th:last-child,
table tr td:last-child {
    margin-bottom: 0;
}
```



###### ==引用==

```css
/*左边竖线颜色、引言字体等设置*/
blockquote {
    border-left: 4px solid #008000;
    padding: 0 15px;
    color: #777777;
    font-weight: bold;
}
blockquote blockquote {
    padding-right: 0;
```

##### e.保存修改

.css的文件命名时，避免出现大写字母和空格键，空格键为转化为“-”，中文名字也是支持的，不过建议还是用英文，完成.css文件代码后，复制到themes文件夹中，即可在**<font color='green'>主题</font>**栏下来列表中查看、选择。

##### f.颜色提取器

修改主题的过程中，最常用到的就是颜色了，以下两个网站供参考：

[Encycolorpedia](https://encycolorpedia.cn/1db213)

[HTML Color Codes](https://html-color-codes.info/) 



##### g.取更多主题

通过以下路径：**<font color='green'>文件</font>** > **<font color='green'>偏好设置</font>** > **<font color='green'>外观</font>** > **<font color='green'>获取主题</font>**，获取更多的主题。

![image09](D:\Program Files\Typora\文件存档\Typora使用教程\Typora使用教程.assets\image09.png)

下载主题后解压，将后缀为.css的文件复制theme文件夹里，即可在**<font color='green'>主题</font>**栏下来列表中查看、选择。

##### h.开发者工具修改样式

还有一个途径修改样式，打开**<font color='green'>开发者工具</font>**，按下图所示步骤修改。

![image-20200916055659919](D:\Program Files\Typora\文件存档\Typora使用教程\image-20200916055659919.png)



![image10](D:\Program Files\Typora\文件存档\Typora使用教程\Typora使用教程.assets\image10.png)

#### 3.3.2 支持HTML元素

不在Markdown 涵盖范围之内的标签，都可以直接在文档中用HTML 撰写。

目前支持的HTML元素有：\<kbd><font color='green'>（**键盘文本**）</font>、 \<b><font color='green'>**（加粗）**</font>、\<i><font color='green'>**（斜体）**</font>、\<em><font color='green'>**（斜体）**</font>、\<sub><font color='green'>**（下标）**</font>、\<sup><font color='green'>**（上标）**</font>、\<br>**<font color='green'>（换行）</font>**、\<center>**<font color='green'>（居中）</font>**等。

\<kbd>应用实例：

> <u>代码</u>：
>
> ```html
> 使用<kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>Delete</kbd>可以打开任务管理器。
> ```
>
> <u>输出结果</u>：
>
> 使用<kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>Delete</kbd>可以打开任务管理器。

综合应用实例：

> <u>代码</u>：
>
> ```html
> <center><span style="color:white;background:green;font-size:2em;font-family:Arial,Helvetica, sans-serif;padding-left:0.5em;padding-right:0.5em;padding-top:0.5em;padding-bottom:0.5em;line-height:2em;"><b><i>一个神奇的公式&nbsp <br>E=mc<sup>2</sup></i></b></span></center>
> ```
>
> <u>输出结果</u>：
>
> <center><span style="color:white;background:green;font-size:2em;font-family:Arial,Helvetica, sans-serif;padding-left:0.5em;padding-right:0.5em;padding-top:0.5em;padding-bottom:0.5em;line-height:2em;"><b><i>一个神奇的公式&nbsp <br>E=mc<sup>2</sup></i></b></span></center>

#### 3.3.3 特殊字符

| 结果 |    代码    |        描述         |
| :--: | :--------: | :-----------------: |
|  "   |  `&quot;`  |        引号         |
|  '   |  `&apos;`  |        撇号         |
|  &   |  `&amp;`   |        和号         |
|      |  `&nbsp;`  |        空格         |
|  ©   |  `&copy;`  |        版权         |
|  ®   |  `&reg;`   |      注册商标       |
|  ™   | `&trade;`  |   商标（注册中）    |
|  ±   | `&plusmn;` |       正负号        |
|  ÷   | `&divide;` |         除          |
|  ×   | `&times;`  |         乘          |
|  °   |  `&deg;`   |         度          |
|  ¹   |  `&sup1;`  |        上标¹        |
|  ²   |  `&sup2;`  |        上标²        |
|  ³   |  `&sup3;`  |        上标³        |
|  ´   | `&acute;`  |      半角引号       |
|  <   |   `&lt;`   |        小于         |
|  >   |   `&gt;`   |        大于         |
| &ne; |   `&ne;`   |       不等于        |
| &le; |   `&le;`   |      小于等于       |
| &ge; |   `&ge;`   |      大于等于       |
|  ¥   |  `&yen;`   |         元          |
|  £   | `&pound;`  |        英镑         |
|  €   |  `&euro;`  |        欧元         |
|  ¢   |  `&cent;`  |         分          |
|  ½   | `&frac12;` |      二分之一       |
|  ¼   | `&frac14;` |      四分之一       |
|  ¾   | `&frac34;` |      四分之三       |
|  §   |  `&sect;`  |      章节符号       |
|  ¦   | `&brvbar;` |       断竖线        |
|  ¶   |  `&para;`  |      段落符号       |
|  x²  |  `$x^2$`   | x的平方（数学公式） |

#### 3.3.4 转义

Typora属于Markdown编辑器的一种。Markdown 使用了很多特殊符号来表示特定的意义，如果需要显示特定的符号则需要使用转义字符，Markdwon 使用反斜杠转义特殊字符，即\\+符号。

> <u>代码</u>：
>
> ```
> **文本加粗** 
> \*\* 正常显示星号 \*\*
> ```
>
> <u>输出结果</u>：
>
> ​		**文本加粗**
>
> ​		\*\*正常显示星号\*\*

Markdown 支持以下这些符号前面加上反斜杠来帮助插入普通的符号：

```
\\		反斜线
\`		反引号
\*		星号
\_		底线
\{ \}	花括号
\[ \]	方括号
\( \)	括号
\#		井字号
\+		加号
\-		减号
\.		英文句号
\!		感叹号
```

#### 3.3.5 高级链接

[百度](1)

[1]:www.baidu.com	"百度"

#### 3.3.6 高级插入图片

[图片的替代问题][1]

[1]:www.baidu.com	"图片地址"

#### 3.3.7 格式转换（Pandoc）

Typora默认支持导出PDF、HTML格式，如果需要导出Word、EPUB等格式，则需要安装Pandoc软件。

点击下载：[Pandoc](https://github.com/jgm/pandoc/releases/tag/2.10.1)

