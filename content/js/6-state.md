### JavaScript Date（日期）对象
日期对象用于处理日期和时间。

1.
>返回当日的日期和时间
如何使用 Date() 方法获得当日的日期。

```js
<html>
<body>

<script type="text/javascript">

document.write(Date())

</script>

</body>
</html>


打印结果为
Sat Jul 29 2017 21:55:10 GMT+0800 (CST)
```


2.getTime()
getTime() 返回从 1970 年 1 月 1 日至今的毫秒数。


```js
<html>
<body>

<script type="text/javascript">
var d=new Date();
document.write("从 1970/01/01 至今已过去 " + d.getTime() + " 毫秒");
</script>

</body>
</html>


打印结果为:
从 1970/01/01 至今已过去 1501336926826 毫秒

```


3.setFullYear()
如何使用 setFullYear() 设置具体的日期。

```js
<html>
<body>

<script type="text/javascript">

var d = new Date()
d.setFullYear(1992,10,3)
document.write(d)

</script>

</body>
</html>


打印结果为:
Tue Nov 03 1992 22:03:47 GMT+0800 (CST)
```


4.toUTCString()
如何使用 toUTCString() 将当日的日期（根据 UTC）转换为字符串。

```js
<html>
<body>

<script type="text/javascript">

var d = new Date()
document.write (d.toUTCString())

</script>

</body>
</html>


打印结果为：
Sat, 29 Jul 2017 14:06:12 GMT
```


5.getDay()
如何使用 getDay() 和数组来显示星期，而不仅仅是数字。

```js
