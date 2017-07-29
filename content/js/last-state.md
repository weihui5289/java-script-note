Java Script 基础

一、 JS的简介

JavaScript是一种网页编程技术，经常用于创建动态交互网页

JavaScript是一种基于对象和事件驱动的解释性脚本语言，类似C语言和Java的语法

事先不编译；逐行执行；无需进行严格的变量声明；内置大量现成对象，编写少量程序可以完成目标

不同的浏览器甚至同一浏览器的不同版本对JavaScript的支持程度都不一样

二、 JS的基本语法
  - 1.如何实现JavaScript
  (1)如何把JavaScript代码放到HTML页面里  

  使用`<script>标签,直接在HTML代码里加入JavaScript代码`
  (1)如何把JavaScript代码放到HTML页面里  
  使用`<script>`标签,直接在HTML代码里加入JavaScript代码
  ```js
  <html>
    <body>
      <script language="javascript" type="text/javascript">  alert("消息");
      </script>
    </body>
  </html>
  ```

- 2.使用`<script stc=”XXX.js”>`调用外部的JavaScript(.js文件)
  ```js
  <html>
    <body>  
      <script language="javascript" type="text/javascript" src="JavaScript.js">  
      </script>
    </body>
  </html>
  ```

  - 3.js注释 //

  - 4.JavaScript代码块  JavaScript可以分批的组合起来，使用“{”“}”把多条语句括起来组成代码块。代码块的作用是一并的执行语句序列。

  ```js
  <script language="javascript" type="text/javascript"> 
   {   document.write("<h1>This is a header</h1>");  
       document.write("<p>This is a paragraph</p>");  
       document.write("<p>This is another paragraph</p>"); 
    } 
  </script> 

  ```
