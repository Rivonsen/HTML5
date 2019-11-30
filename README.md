<!-- 
1、使用<!DOCTYPE html>申明这是一个html文件
2、<html>元素是HTML页面的根元素
3、<head>元素包含文档的元数据。
4、<title>包含文档的标题
5、<body>包含文档的可见内容。
6、<h1>定义一个大标题
7、<p>定义一个段落 
8、图像的名称和尺寸是以属性的形式进行定义的，如：<img src="/image/logo.png" width = "200" height = "200"/>
9、链接是通过<a></a>来定义的，如:<a href="www.baidu.com"></a>
10、<br>表示换行，无结束标签
11、<hr>标签定义水平线
12、注释符号
13、当显示页面时，浏览器会移除源代码中多余的空格和空行。所有连续的空格或者空行都会被算作为一个空格。
14、在<head>中可以添加<title>,<meta>,<script>,<noscript>,<base>,<style>,<link>
15、<base>标签描述了基本的链接地址，该标签作为html文档中多有的链接标签的默认链接。
16、<link>标签定义了文档与外部资源之间的关系，link标签通常用于链接到样式表。
17、<style>标签定义了HTML文档的样式文件引用地址，在style元素中可以直接添加样式来渲染HTML文档。
example：
<head>
<style type = "text/css">
body {background-color:yellow}
p {color:blue}
</style>
</head>

18、块级元素和内联元素，<div>元素是块级元素，浏览器会在其前后显示折行。用于文档布局。
example：
<div>
<h1>这是一个块级元素</h1>
</div>

<span>内联元素就相当于oc中的富文本


-->


实例：
<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8">
        <title>文档标题</title>    
    </head>
    <body>
        <h1>我的第一个标题</h1>
        <p>我的第一个内容</p>
    </body>
</html>>

属性：
1、属性一般描述于开始标签
2、属性总是以键值对的形式出现，即key = value