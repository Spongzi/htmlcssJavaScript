HTML学习的第一天

head属性是标题

body是主体

p代表一个段落

h1~h6代表着标题标签

img的头是代表着图片的存放

hr/是水平线

em是斜体

u是文字下划线

strong是文字加粗

strike是带删除线的文字

h中align可以赋一些属性，比如center是居中对齐left是左对齐right是右对齐

pre在这里面写的文字格式可以完整的在网页中显示出来

a href 在这个里面可以赋值超链接！

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=\, initial-scale=1.0">
    <title>第一天</title>
</head>
<body>
    <h1>这是一个标题</h1>
    <p>这是一个段落</p>
    <h2>这是一个标题</h2>
    <a href="https://www.runoob.com/html/html-basic.html">这是一个超链接</a>
    <br>
    <img loading="lazy" src="https://i.loli.net/2021/07/09/b3DlgYw1WrnTvRp.png" width="800" height="800" />
    <br>
    <h2>hr是水平线</h2>
    <hr/>
    <p>我是混子</p>
    <br>
    <em>我是斜体</em>
    <br>
    <u>我是下划线</u>
    <br>
    <strong>我是加粗</strong>
    <br>
    <strike>带删除线的文字</strike>
    <br>
    <p>我是傻逼<sup>2</sup></p>
    <p>你是傻逼<sub>我觉得你说的对</sub></p>
    <h1 align="center">这是个居中对齐</h1>
    <br>
    <h1 align="left">这是个左对齐</h1>
    <br>
    <h1 align="right">这是个右对齐</h1>
    <br>
    <pre>
        这个
            可以   
                保留
            样式
        不会自己消去空格
    </pre>
    <!-- hr我是一条线 -->
    <hr>
    <p>这个是个段落标识</p>
</body>
</html>
```

