### JavaScript Math（算数）对象

Math（算数）对象的作用是：执行常见的算数任务。

1. round()
如何使用 round()。四舍五入

```js
<html>
<body>

<script type="text/javascript">

document.write(Math.round(0.60) + "<br />")
document.write(Math.round(0.50) + "<br />")
document.write(Math.round(0.49) + "<br />")
document.write(Math.round(-4.40) + "<br />")
document.write(Math.round(-4.60))

</script>

</body>
</html>


输出结果：
1
1
0
-4
-5

```

2. random()
如何使用 random() 来返回 0 到 1 之间的随机数。

```js
<html>
<body>

<script type="text/javascript">

document.write(Math.random())

</script>

</body>
</html>



输出结果：
0.16323386482758995

```


3. max()
如何使用 max() 来返回两个给定的数中的较大的数。（在 ECMASCript v3 之前，该方法只有两个参数。）

```js
<html>
<body>

<script type="text/javascript">

document.write(Math.max(5,7) + "<br />")
document.write(Math.max(-3,5) + "<br />")
document.write(Math.max(-3,-5) + "<br />")
document.write(Math.max(7.25,7.30))

</script>

</body>
</html>


输出结果：
7
5
-3
7.3

```


4. min()
如何使用 min() 来返回两个给定的数中的较小的数。（在 ECMASCript v3 之前，该方法只有两个参数。）




### 算数值
JavaScript 提供 8 种可被 Math 对象访问的算数值：
- 常数
- 圆周率
- 2 的平方根
- 1/2 的平方根
- 2 的自然对数
- 以 2 为底的 e 的对数
- 以 10 为底的 e 的对数


是在 Javascript 中使用这些值的方法：（与上面的算数值一一对应）
- Math.E
- Math.PI
- Math.SQRT2
- Math.LN2
- Math.LN10
- Math.LOG2E
- Math.LOG10E
