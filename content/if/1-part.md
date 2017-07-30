### JavaScript If...Else 语句
件语句
通常在写代码时，您总是需要为不同的决定来执行不同的动作。您可以在代码中使用条件语句来完成该任务。
在 JavaScript 中，我们可使用以下条件语句：
>if 语句 - 只有当指定条件为 true 时，使用该语句来执行代码

>if...else 语句 - 当条件为 true 时执行代码，当条件为 false 时执行其他代码

>if...else if....else 语句 - 使用该语句来选择多个代码块之一来执行

>switch 语句 - 使用该语句来选择多个代码块之一来执行


If 语句
只有当指定条件为 true 时，该语句才会执行代码。

```js
if (条件)
  {
  只有当条件为 true 时执行的代码
  }
```

2. If...else 语句
请使用 if....else 语句在条件为 true 时执行代码，在条件为 false 时执行其他代码。

```js
if (条件)
  {
  当条件为 true 时执行的代码
  }
else
  {
  当条件不为 true 时执行的代码
  }


  ```


  3.If...else if...else 语句
  使用 if....else if...else 语句来选择多个代码块之一来执行。
  ```js
  if (time<10)
  {
  x="Good morning";
  }
else if (time<20)
  {
  x="Good day";
  }
else
  {
  x="Good evening";
  }

  打印结果：
  Good day

  ```


  4. JavaScript Switch 语句
  请使用 switch 语句来选择要执行的多个代码块之一。
  ```js
    witch(n)
  {
  case 1:
    执行代码块 1
    break;
  case 2:
    执行代码块 2
    break;
  default:
    n 与 case 1 和 case 2 不同时执行的代码
  }
  ```

  工作原理：首先设置表达式 n（通常是一个变量）。随后表达式的值会与结构中的每个 case 的值做比较。如果存在匹配，则与该 case 关联的代码块会被执行。请使用 break 来阻止代码自动地向下一个 case 运行。

  ```js
  var day=new Date().getDay();
switch (day)
{
case 0:
  x="Today it's Sunday";
  break;
case 1:
  x="Today it's Monday";
  break;
case 2:
  x="Today it's Tuesday";
  break;
case 3:
  x="Today it's Wednesday";
  break;
case 4:
  x="Today it's Thursday";
  break;
case 5:
  x="Today it's Friday";
  break;
case 6:
  x="Today it's Saturday";
  break;
}

```

5.
