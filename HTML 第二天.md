HTML第二天

| 标签                                                    | 描述                               |
| :------------------------------------------------------ | :--------------------------------- |
| [](https://www.runoob.com/tags/tag-head.html)  head     | 定义了文档的信息                   |
| [](https://www.runoob.com/tags/tag-title.html)    title | 定义了文档的标题                   |
| [](https://www.runoob.com/tags/tag-base.html)base       | 定义了页面链接标签的默认链接地址   |
| [](https://www.runoob.com/tags/tag-link.html)link       | 定义了一个文档和外部资源之间的关系 |
| [](https://www.runoob.com/tags/tag-meta.html)meta       | 定义了HTML文档中的元数据           |
| [](https://www.runoob.com/tags/tag-script.html)scipt    | 定义了客户端的脚本文件             |
| [](https://www.runoob.com/tags/tag-style.html)style     | 定义了HTML文档的样式文件           |

现在通常使用font-family（字体），color（颜色），和font-size（字体大小）属性来定义文本样式

背景色属性（background-color）

在 HTML 中，图像由<img> 标签定义。

<img> 是空标签，意思是说，它只包含属性，并且没有闭合标签。

要在页面上显示图像，你需要使用源属性（src）。src 指 "source"。源属性的值是图像的 URL 地址。

alt 属性用来为图像定义一串预备的可替换的文本。

替换文本属性的值是用户定义的。

```html
<img src="C:/Program%20Files/Typora/boat.gif" alt="Big Boat">
```

在浏览器无法载入图像时，替换文本属性告诉读者她们失去的信息。此时，浏览器将显示这个替代性的文本而不是图像。为页面上的图像都加上替换文本属性是个好习惯，这样有助于更好的显示信息，并且对于那些使用纯文本浏览器的人来说是非常有用的。

## HTML 图像- 设置图像的高度与宽度

height（高度） 与 width（宽度）属性用于设置图像的高度与宽度。

属性值默认单位为像素:

```html
<img src="C:/Program%20Files/Typora/pulpit.jpg" alt="Pulpit rock" width="304" height="228">
```

**提示:** 指定图像的高度和宽度是一个很好的习惯。如果图像指定了高度宽度，页面加载时就会保留指定的尺寸。如果没有指定图片的大小，加载页面时有可能会破坏HTML页面的整体布局。

float:righ--->一个带图片的段落，图片浮动在这个文本的右边。

float:left--->一个带图片的段落，图片浮动在这个文本的左边。

## HTML 表格

每个表格从一个 table 标签开始。 每个表格行从 tr 标签开始。 每个表格的数据从 td 标签开始。

```html
    <table border="1">
        <tr>
            <td>Row 1, cell 1</td>
            <td>Row 1, cell 2</td>
        </tr>
    </table>
```

border 是设定边框宽度的！！！

## HTML 表格表头

表格的表头使用 <th> 标签进行定义。

大多数浏览器会把表头显示为粗体居中的文本：

```html
<table border="1">
    <tr>
        <th>Header 1</th>
        <th>Header 2</th>
    </tr>
    <tr>
        <td>row 1, cell 1</td>
        <td>row 1, cell 2</td>
    </tr>
    <tr>
        <td>row 2, cell 1</td>
        <td>row 2, cell 2</td>
    </tr>
</table>
```

单元格跨两列：colspan="2"

单元格跨两行:border="1"

```html
<!DOCTYPE html>
<html>
<head> 
<meta charset="utf-8"> 
<title>菜鸟教程(runoob.com)</title> 
</head>
<body>

<h4>单元格跨两列:</h4>
<table border="1">
<tr>
  <th>Name</th>
  <th colspan="2">Telephone</th>
</tr>
<tr>
  <td>Bill Gates</td>
  <td>555 77 854</td>
  <td>555 77 855</td>
</tr>
</table>

<h4>单元格跨两行:</h4>
<table border="1">
<tr>
  <th>First Name:</th>
  <td>Bill Gates</td>
</tr>
<tr>
  <th rowspan="2">Telephone:</th>
  <td>555 77 854</td>
</tr>
<tr>
  <td>555 77 855</td>
</tr>
</table>

</body>
</html>
```

单元格边距：cellpadding

```HTML
<table border="1" 
cellpadding="10">
<tr>
  <td>First</td>
  <td>Row</td>
</tr>   
<tr>
  <td>Second</td>
  <td>Row</td>
</tr>
</table>
```

单元格间距：cellspacing

```html
<!DOCTYPE html>
<html>
<head> 
<meta charset="utf-8"> 
<title>菜鸟教程(runoob.com)</title> 
</head>
<body>

<h4>没有单元格间距:</h4>
<table border="1">
<tr>
  <td>First</td>
  <td>Row</td>
</tr>
<tr>
  <td>Second</td>
  <td>Row</td>
</tr>
</table>

<h4>单元格间距="0":</h4>
<table border="1" cellspacing="0">
<tr>
  <td>First</td>
  <td>Row</td>
</tr>
<tr>
  <td>Second</td>
  <td>Row</td>
</tr>
</table>

<h4>单元格间距="100":</h4>
<table border="1" cellspacing="10">
<tr>
  <td>First</td>
  <td>Row</td>
</tr>
<tr>
  <td>Second</td>
  <td>Row</td>
</tr>
</table>

</body>
</html>
```

![](https://i.loli.net/2021/07/13/2hj1mlfq5yRYbH8.png)

