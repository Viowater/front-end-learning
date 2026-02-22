# 1.概述
## 1.1
    html，全称hypertext markup language（超文本标记语言）
    通过一系列“标签(元素/容器)”来定义 文本 图像 连接 等

## 1.2
    有双标签和单标签
    通过添加属性来提供更多信息
    属性形式一般为： 
        属性名="属性值"
    
## 1.3
    元素内若有多个空白，只会视为一个

## 1.4
输入 ! 然后tab即可自动键入通用模块，包含

    <!DOCTYPE html>     声明本文件时html文件
    <html lang="en">    根元素，包含页面所有内容
    <head>              “头” 一些不想向用户显示的内容
        <meta charset="UTF-8">      字符编码
        <meta name="viewport" content="width=device-width, initial-scale=1.0">          视口元素？
    <title>html_PRAC1</title>       页面标题，也是收藏网页时的描述文字
    </head>
    <body>  “身体”真正显示在网页中的

    </body>
    </html>


## 1.5
    注释写法： <!--注释内容-->
   

# 字符引用
    在html中显示尖括号，引号，&的方法：
    < = &lt (less than)
    > = &gt (greater than)
    " = &quot (quotation)
    ' = &apos 似乎只在xml有效，html应用 &#39
    & = &amp  (ampersand)


# 块级元素和行内元素
    1.块元素：
    通常用于组织和布局页面的主要结构和内容，例如段落，标题，表格，列表等。
    用于创建页面的主要部分，将内容分割成逻辑块

    其占据页面的一整行，并通常新开一行
    可以包含其他块/行内元素
    常见的有:div p h1-h6 ul ol li table form 

    2.行内元素：
    通常用于添加文本样式或为文本中的一部分应用样式。也可以在文本中插入其他元素，如超链接等

    只占据内容所需宽度，不会新开一行
    只能包含行内元素
    常见：span a strong em img br input 
 

