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
    