### JavaScript RegExp 对象

什么是 RegExp？
RegExp 是正则表达式的缩写。
当您检索某个文本时，可以使用一种模式来描述要检索的内容。RegExp 就是这种模式。
简单的模式可以是一个单独的字符。
更复杂的模式包括了更多的字符，并可用于解析、格式检查、替换等等。
您可以规定字符串中的检索位置，以及要检索的字符类型，等等。


定义 RegExp
RegExp 对象用于存储检索模式。
通过 new 关键词来定义 RegExp 对象。以下代码定义了名为 patt1 的 RegExp 对象，其模式是 "e"：


1. RegExp 对象的方法
   RegExp 对象有 3 个方法：test()、exec() 以及 compile()。

  ```js
  var patt1=new RegExp("e");

  document.write(patt1.test("The best things in life are free"));
  ```

2. exec()
exec() 方法检索字符串中的指定值。返回值是被找到的值。如果没有发现匹配，则返回 null。

```js
var patt1=new RegExp("e");

document.write(patt1.exec("The best things in life are free"));
```

3. compile()
compile() 方法用于改变 RegExp。
compile() 既可以改变检索模式，也可以添加或删除第二个参数。
