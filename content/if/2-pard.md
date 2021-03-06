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





### 相互比较的操作

1. ** 相等运算符：== **
相等运算符比较两个值，如果它们是同等，返回 true，如果它们不等，返回false。
```js
1 == 1 // true
1 == 2 // false
1 == '1' // true
"3" == 3 // true
```


2. ** 相等运算符：== **
是相对于相等操作符（==）的一种操作符。与相等操作符不同的是全等比较严格，它会同时比较元素的值和 数据类型。

```js
3 === 3 // true
3 === '3' // false
```


3. ** 不相等运算符（!=） **
与相等运算符是相反的。

不相等运算符中，如果“不为真”并且返回 false 的地方，在相等运算符中会返回true，反之亦然。

与相等运算符类似，不相等运算符在比较的时候也会转换值的数据类型。

```js
1 != 2 // true
1 != "1" // false
1 != '1' // false
1 != true // false
0 != false // false
```

3. ** 不相等运算符（!=） **

与全等运算符是相反的。
```js
3 !== 3 // false
3 !== '3' // true
4 !== 3 // true
```

4. 大于运算符（>）
```js
5 > 3  // true
1 > 9 // false
```

5. 大于等于 运算符（>=）
```js
6 >= 6 // true
7 >= '3' // true
2 >= 3 // false
'7' >= 9 // false
```

6.小于 运算符（<）   比较两个数字的大小
```js
2 < 5 // true
'3' < 7 // true
5 < 5 // false
3 < 2 // false
'8' < 4 // false
```

7. 逻辑与 运算符（&&）
需要在一次判断中做多个操作。当且仅当运算符的左边和右边都是 true

```js
if (num > 5 && num < 10) {
return "Yes";
}
return "No";
```
