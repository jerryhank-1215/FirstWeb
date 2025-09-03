# Hello! Welcome Home : )

> An awesome project. ----from Jerry Fernando  
>
> Created in 2025/8/25 
  
---
# **Hank** *EAT* ~~*" 粑粑 "*~~ ***" BABA "***
>啊，***没座**~!*  
>
>**阿坤** 啥都能接   

<br>
<img src="fenda.jpg" alt="没座" width="300" height="150"></img>

<br>

---
### 吟唱： 
* 第一阶段： 
    >"他们朝~~ 我扔 **泥巴** "  
     >" 我拿 **泥巴** 种 **荷花** ~~“  

    >" 他们朝~~ 我丢 **石头** "  
     >"我拿 **石头** 砌 **小楼**~~ “  

  * ***哦~ 哦~ 哦~ 哦~ 哦~***  
    ***哦~ 哦~ 哦~ 哦~ 哦~***

* 第二阶段：
    >"他们朝~~ 我扔 **白菜** "  
    >"我拿 **白菜 炒盘chai~~** "

    >"他们朝~~ 我扔 ***粑粑*** "  
    >“我拿 ***粑粑*** 做**蛋挞**~~ ”  

    * ***哦~ 哦~ 哦~ 哦~ 哦~***  
      ***哦~ 哦~ 哦~ 哦~ 哦~***

---
> 啊, ***没座**~!*  
>
> *(吟唱结束)*

---

> |  选手  |  评分  |
> |:-:|-:|
>|杨坤       |    1分|
>|四川芬达   |    5分|
>|Hank      |  999分| 




---

# Math Formula
> $if:  ax^2 + bx + c = 0 $  
>
> $$ \Delta = \sqrt{b^2-4ac} $$
>
> $$ x_1= (-b+\sqrt{\Delta})/2a$$

# Python Code
``` 
print("hello world!") 
```

---
# Web前端学习

## HTML

> HTML通过一系列的 **标签** 来定义文本、图像、链接  
> HTML标签是由 **尖括号** 包围的关键字

标签通常成对出现  
以下为**双标签** #*用于有内容的元素*

``` HTML
<p>这是一个段落</p>
<h1>这是一个标题</h1>
<a jerryandhank1215="#">这是一个超链接</a>
```

除了双标签，也存在**单标签** #*用于无内容的元素*

``` HTML
<input type="text">
<br> #换行标签
<hr> #分割线标签
```

## HTML 文件结构

```HTML
<!-- 这里放置文档的元信息 -- >
<! DOCTYPE html>          #告诉浏览器此为HTML文件
<html>
  <head>
    <!-- 这里放置文档的元信息 -- >
    <title>文档标题</title>
    <meta charset="UTF-8">
    <!-- 连接外部样式表或脚本文件等 -- >
    <link rel="stylesheet" type="text/css" href="styles.css">
    <script src="script.js"></script>
  </head>
  <body>
    <!-- 这里放置页面内容 -- >
    <h1>这是一个标题</h1>
    <p>这是一个段落。</p>
    <a href="https://www.example.com">这是一个链接</a>
    <!-- 其他内容 -- >
  </body>
</html>
```
$line 3, line 19$ 为 HTML 标签对, 表明文档 **起始点**  
$head$ 标签对， 包含一些文件的 **原信息**  
$body$ 标签对， 包含 **实际显示在浏览器页面的内容**

---


## HTML **文本** 标签

1. **标题** 标签  
  ```<h1> </h1>```  
  ```<h2> </h2>```  
  一直到 **h6**

2. **段落** 标签  
  
    ```<p> </p> ```  

    **更改文本样式：**  
    
    1. **加粗**（bold）：  
      
        效果： <b>加粗</b>
      
        ```HTML
        <p>

        <b> 加粗 </b> 
        or 
        <strong> "jiacu" </strong>
    
        </p>
        ```

    2. **斜体**：  
      效果：<i>斜体</i>， <em>xieti</em>，*斜*  
        
        ```HTML
        <i>斜体</i>  
        or 
        <em>xieti</em>
        ```  

    3. **下划线**：  
      效果：<ins>下划线</ins>， <u>下划线</u>     
        
        ```HTML
        <ins>下划线</ins>
        or 
        <u>下划线</u>
        ```
        
    4. **删除线**:
      效果： ~~删除线~~    
        
        ```HTML
        <s>删除线</s>
        or
        <del>删除线</del>
        ```
        
    5. 其他：  
      效果：  
      <mark>标记</mark> Code: ```<mark>标记</mark>```   
      <small>小号</small> Code: ```<small>小号</small>```  

3. 表格标签：  
  
    | 标签 | 表示 |  
    |-|-|  
    |**tr** <i> (tablerow) </i>   |表示行|  
    |**th** <i> (tableheader) </i> |表示表头|    
    |**td** <i> (tabledata) </i>  |表示单元格|  

  
    效果：
    <table>
      <tr> 
        <th>姓名</th>
        <th>评分</th>
      </tr>
      <tr> 
        <td>杨坤</td>
       <td>0</td>
      </tr>
    </table>
  
    ```HTML
   <table>
    <tr> 
      <th>姓名</th>
      <th>评分</th>
    </tr>
    <tr> 
      <td>杨坤</td>
      <td>0</td>
    </tr>
    </table>
    ```

4. 列表标签：
    <ul>
    <li>无序列表1</li>
    <li>无序列表2</li>
    <li>无序列表3</li>
    </ul>

    <ol>
    <li>有序列表1</li>
    <li>有序列表2</li>
    <li>有序列表3</li>
    </ol>    

    ```HTML
    <ul>
        <li>无序列表1</li>
        <li>无序列表2</li>
        <li>无序列表3</li>
    </ul>

    <ol>
        <li>有序列表1</li>
        <li>有序列表2</li>
        <li>有序列表3</li>
    </ol>
    ```  

## HTML 标签**属性**
  <h3>HTML常见标签属性</h3>
  <hr>
  <h3> a的 herf 超链接属性 </h3>
  （其他网页链接、文件路径、电子邮箱地址、手机号码）
  <br>
  <a href="https://jerryhank-1215.github.io/FirstWeb/#/?id=html">MyFirstWeb</a>
  默认覆盖当前页面

<br>

  ```HTML
  <a href="https://example.com"> example </a>
  ```

  <h3> a的 target 属性</h3>
  <hr>
  （决定链接打开方式）
  <br>
  （_self 当前窗口打开， _blank 新窗口打开， _parent 父窗口打开， _top 全屏打开）
  <hr>
    
  <a href="https://jerryhank-1215.github.io/FirstWeb/#/?id=html" target="_blank">MyFirstWeb</a>
  新窗口打开
  
  <a href="https://jerryhank-1215.github.io/FirstWeb/#/?id=html" target="_parent">MyFirstWeb</a>
  父窗口打开
  
  <a href="https://jerryhank-1215.github.io/FirstWeb/#/?id=html" target="_top">MyFirstWeb</a>
  全屏打开
  <br>

  ```HTML
   <a href="https://example.com" target="_top or _blank or _parent"> 
   example </a>
  ```

    
    
  <h3> a的 download 属性 </h3>
  <hr>
  （下载属性，点击链接后会下载而不是跳转）
    <br>
    <a href="https://th.bing.com/th/id/OIP.QSkNF06A6BFJ37TPgSK0-QHaEo?w=303&h=189&c=7&r=0&o=7&dpr=1.6&pid=1.7&rm=3" download>下载坤哥</a>
    <br>

  <h3> img的 src 属性 </h3>
  <hr>  
    （决定 <b>图片路径</b> ，可以是相对路径，也可以是绝对路径，还可以是网络路径url）
    <br>
    <img src="https://th.bing.com/th/id/OIP.QSkNF06A6BFJ37TPgSK0-QHaEo?w=303&h=189&c=7&r=0&o=7&dpr=1.6&pid=1.7&rm=3" alt="">嘻嘻
    <br>

  <h3> img的 alt 属性 </h3>
  <hr>
    （当图片无法显示时，显示的替代文本）
    <br>
    <br>
    <img src="https://th.bing.com" alt="坤哥无法显示">
    <br>

  <h3>img 调整图像大小</h3>
  <hr>
  （width 宽度 height 高度）
    <br>
    <img src="https://th.bing.com/th/id/OIP.QSkNF06A6BFJ37TPgSK0-QHaEo?w=303&h=189&c=7&r=0&o=7&dpr=1.6&pid=1.7&rm=3" alt="" height="114" width="514">
    <br>
    帅吧？
    <br>


## HTML **区块**

### 块元素
（通常用于组织和布局页面的 **主要结构** 和 **内容**）   
- 块级元素通常会 **从新行开始** ，并占据 **整行**（浏览器中）的宽度  
  以呈现出 **独立的内容块**
- 可包含其他 **块级元素** 和 **行内元素**
- 常见的块级元素：``<div>`` , ``<p>`` , ``<h1>到<h6>`` , ``<ul>``, ``<ol>`` , ``<li>`` , ``<table>`` , ``<form>``


### 行内元素
(通常用于 **添加文本样式** 或为文本中的 **一部分应用样式**)  
- 行内元素通常在同一行内呈现, 只占据其内容所需的宽度,   
  **不会独占一行**。
- 行内元素不能包含块级元素, 但可以包含其他行内元素。
- 常见的行内元素: `<span>` , `<a>` , `<strong>` , `<em>` , `<img>` , `<br>` , `<input>`等。


## HTML **表单**
<h3>表单：</h3>
    表单是一种带有空格可用于书写以及能选择和勾选相似内容的文件<br>  
    如B站注册页面的 “账号” “密码” 的空格栏  
      
<h3>使用：</h3>
    使用 <i>form</i> 作为容器 <br>     
    使用 <i>label</i> 或者<i> span</i> 输入文字 <br>
    使用<i> input</i> 达到交互 <br>
    placeholder 显示灰色字用于提示用户<br>  
    value 显示黑字而且框中有实值  
    <br>
    <br>
    - 特别说明：<br>
    若<b><i> label标签</i></b> 的属性<b><i> for=“”</i></b> 中的内容与下面<b><i> input标签</b></i> 的<b><i> id属性</b></i> 中的 内容相同，<br>
    则在网页中 <b><i>点击label</b></i> 的文字即可触发 <b><i>input</b></i> (不信你试试), <br>
    可方便手机用户 
    <br> 
    <br>


```HTML
<form action="">
        <label for="name">姓名</label>
        <input id="name" type="text" placeholder="please type your name">   ##: 使用“type”属性说明是输入“文字”还是选择“选项”
        <br>

        <span for="point">评分</span>
        <input id="point" type="text" value="already have value">  ##：type=“text” 说明是输入框
        <br>

        <label for="opinion">赞同？</label>
        <br>

        <label for="opinion">是</label>
        <input type="radio" id="opinion" name="agree">   ##:type=“ratio” 说明是选项
        <label for="opinion">否</label>
        <input type="radio" id="opinion" name="agree">   ##:由于id=“opinion” 避免了多选
    </form>   
```
<h3>效果：</h3>

<form action="">
  <label for="name">姓名</label>
  <input id="name" type="text" placeholder="please type your name">
  <br>

  <span for="point">评分</span>
  <input id="point" type="text" value="already have value">
  <br>
  <label for="opinion">赞同？</label>
  <br>
  <label for="opinion">是</label>
  <input type="radio" id="opinion" name="agree">
  <label for="opinion">否</label>
  <input type="radio" id="opinion" name="agree">
</form>    
    

## CSS

常用于**页面设计**，添加颜色、样式  

### CSS语法
CSS通常由 **选择器、属性 和 属性值** 组成  

```
1     选择器 {
2         属性1： 属性值1；
3         属性2： 属性值2；
4     }
```

1. 选择器的说明中可以写 **无数条** 属性
2. 声明中每一行属性都要以 **英文** 分号结尾
3. 声明中 所有属性和值 都是以 **键值对** 这种形式出现的


```HTML
/*这是一个p标签选择器*/
p {
  color: brown;
  font-size: 16px
}
```

<br>
<br>  


<h1>CSS 导入方式</h1> 

<h3>
    CSS导入方式有三种:
</h3>
    
1. 内联样式（Inline Styles）:直接在HTML标签的`style`属性       

2. 内部样式表（Internal Style Sheets）:在HTML文档的`head`部分使用`style`标签

3. 外部样式表（External Style Sheets）:通过`link`标签链接到外部CSS文件（方便与同一种样式应用在多个网页上）
        
<h3>
  <span  style="background-color:grey; color=black;">
  三种导入方式的优先级：内联样式 > 内部样式表 > 外部样式表
  </span>
</h3>