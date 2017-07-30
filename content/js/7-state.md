### JavaScript Array（数组）对象

1.创建一个新的数组

```js
<html>
<body>

<script type="text/javascript">
var mycars = new Array()
mycars[0] = "Saab"
mycars[1] = "Volvo"
mycars[2] = "BMW"

for (i=0;i<mycars.length;i++)
{
document.write(mycars[i] + "<br />")
}
</script>

</body>
</html>


输出结果
Saab
Volvo
BMW

```


2.
For...In 声明
使用 for...in 声明来循环输出数组中的元素。


```js
<html>
<body>
<script type="text/javascript">
var x
var mycars = new Array()
mycars[0] = "Saab"
mycars[1] = "Volvo"
mycars[2] = "BMW"

for (x in mycars)
{
document.write(mycars[x] + "<br />")
}
</script>
</body>
</html>


输出结果:
Saab
Volvo
BMW

```


3.合并两个数组 - concat()
如何使用 concat() 方法来合并两个数组

```js
<html>
<body>

<script type="text/javascript">

var arr = new Array(3)
arr[0] = "George"
arr[1] = "John"
arr[2] = "Thomas"

var arr2 = new Array(3)
arr2[0] = "James"
arr2[1] = "Adrew"
arr2[2] = "Martin"

document.write(arr.concat(arr2))

</script>

</body>
</html>


输出结果：
George,John,Thomas,James,Adrew,Martin

```


4.用数组的元素组成字符串 - join()
如何使用 join() 方法将数组的所有元素组成一个字符串。

```js
<html>
<body>

<script type="text/javascript">

var arr = new Array(3);
arr[0] = "George"
arr[1] = "John"
arr[2] = "Thomas"

document.write(arr.join());

document.write("<br />");

document.write(arr.join("."));

</script>

</body>
</html>


输出结果：
George,John,Thomas
George.John.Thomas

```


4.文字数组 - sort()
如何使用 sort() 方法从字面上对数组进行排序。

```js
<html>
<body>

<script type="text/javascript">

var arr = new Array(6)
arr[0] = "George"
arr[1] = "John"
arr[2] = "Thomas"
arr[3] = "James"
arr[4] = "Adrew"
arr[5] = "Martin"

document.write(arr + "<br />")
document.write(arr.sort())

</script>

</body>
</html>


输出结果为：
George,John,Thomas,James,Adrew,Martin
Adrew,George,James,John,Martin,Thomas

```

5.数字数组 - sort()
如何使用 sort() 方法从数值上对数组进行排序。

```js
<html>
<body>

<script type="text/javascript">

function sortNumber(a, b)
{
return a - b
}

var arr = new Array(6)
arr[0] = "10"
arr[1] = "5"
arr[2] = "40"
arr[3] = "25"
arr[4] = "1000"
arr[5] = "1"

document.write(arr + "<br />")
document.write(arr.sort(sortNumber))

</script>

</body>
</html>

输出结果为：
10,5,40,25,1000,1
1,5,10,25,40,1000

```
