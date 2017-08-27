### JavaScript变量


* 变量命名规则
JavaScript 变量
与代数一样，JavaScript 变量可用于存放值（比如 x=2）和表达式（比如 z=x+y）。
- 变量可以使用短名称（比如 x 和 y），也可以使用描述性更好的名称（比如 age, sum, totalvolume）。
- 变量必须以字母开头
- 变量也能以 $ 和 _ 符号开头（不过我们不推荐这么做）
- 变量名称对大小写敏感（y 和 Y 是不同的变量）
- 提示：JavaScript 语句和 JavaScript 变量都对大小写敏感。...




* 申明或创建变量
```js
<script language="javascript" type="text/javascript">
   var i=123;//使用var关键字申明变量  
   var s="李志伟";
  temp="直接赋值使用变量";
  //如果您所赋值的变量还未进行过声明，该变量会自动声明。
   document.write(i+" "+s+" "+temp);
</script>

```
* 重新申明变量
```js
<script language="javascript" type="text/javascript">
 var i=123;//使用var关键字申明变量  
 var i;//在重新声明该变量后，变量的值不会被重置或清除
 document.write("i的值是:"+i);//i的值还是123
</script>

```
JavaScript 数据类型
JavaScript 变量还能保存其他数据类型，比如文本值 (name="Bill Gates")。
在 JavaScript 中，类似 "Bill Gates" 这样一条文本被称为字符串。
JavaScript 变量有很多种类型，但是现在，我们只关注数字和字符串。

```js
var pi=3.14;
var name="Bill Gates";
var answer='Yes I am!';
```



一条语句，多个变量
您可以在一条语句中声明很多变量。该语句以 var 开头，并使用逗号分隔变量即可：

```js
var name="Gates", age=56, job="CEO";
```
