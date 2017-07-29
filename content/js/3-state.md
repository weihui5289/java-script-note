### JavaScript 数据类型
* null：空、无。表示不存在，当为对象的属性赋值为null，表示删除该属性
* undefined：未定义。当声明变量却没有赋值时会显示该值。可以为变量赋值为undefined
* number：数值。最原始的数据类型，表达式计算的载体
* boolean：布尔值。最机械的数据类型，逻辑运算的载体
* object：对象。面向对象的基础

1.JavaScript 字符串 String
字符串是存储字符（比如 "Bill Gates"）的变量。
字符串可以是引号中的任意文本。您可以使用单引号或双引号：

```js
var carname="Bill Gates";
var carname='Bill Gates';
```


2.JavaScript 数字 number
JavaScript 只有一种数字类型。数字可以带小数点，也可以不带：

```js
var x1=34.00;      //使用小数点来写
var x2=34;         //不使用小数点来写
```

3.JavaScript 布尔 boolean
布尔（逻辑）只能有两个值：true 或 false。
```js
var x=true
var y=false
```

4.JavaScript 数组 Array
下面的代码创建名为 cars 的数组：

```js
var cars=new Array();
cars[0]="Audi";
cars[1]="BMW";
cars[2]="Volvo";
或者
var cars=new Array("Audi","BMW","Volvo");
或者
var cars=["Audi","BMW","Volvo"];
```

5.JavaScript 对象 object
对象由花括号分隔。在括号内部，对象的属性以名称和值对的形式 (name : value) 来定义。属性由逗号分隔：

```js
var person={firstname:"Bill", lastname:"Gates", id:5566};
```

6.Undefined 和 Null
Undefined 这个值表示变量不含有值。
可以通过将变量的值设置为 null 来清空变量。

```js
cars=null;
person=null;
```


#### 声明变量类型
当您声明新变量时，可以使用关键词 `"new"` 来声明其类型：

```js
var carname=new String;
var x=      new Number;
var y=      new Boolean;
var cars=   new Array;
var person= new Object;
```
