### JavaScript For 循环

JavaScript 循环
如果您希望一遍又一遍地运行相同的代码，并且每次的值都不同，那么使用循环是很方便的。
我们可以这样输出数组的值：

```js
document.write(cars[0] + "<br>");
document.write(cars[1] + "<br>");
document.write(cars[2] + "<br>");
document.write(cars[3] + "<br>");
document.write(cars[4] + "<br>");
document.write(cars[5] + "<br>");
```


```js
for (var i=0;i<cars.length;i++)
{
document.write(cars[i] + "<br>");
}
```


#### 不同类型的循环
- JavaScript 支持不同类型的循环：
- for - 循环代码块一定的次数
- for/in - 循环遍历对象的属性
- while - 当指定的条件为 true 时循环指定的代码块
- do/while - 同样当指定的条件为 true 时循环指定的代码块


1. For 循环
for 循环是您在希望创建循环时常会用到的工具。
下面是 for 循环的语法：

- 语句 1 在循环（代码块）开始前执行
- 语句 2 定义运行循环（代码块）的条件
- 语句 3 在循环（代码块）已被执行之后执行

```js
for (var i=0; i<5; i++)
  {
  x=x + "The number is " + i + "<br>";
  }

  从上面的例子中，您可以看到：
  Statement 1 在循环开始之前设置变量 (var i=0)。
  Statement 2 定义循环运行的条件（i 必须小于 5）。
  Statement 3 在每次代码块已被执行后增加一个值 (i++)。

```

2. 
