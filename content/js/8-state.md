### JavaScript Boolean（逻辑）对象 布尔

1. Boolean（逻辑）对象用于将非逻辑值转换为逻辑值（true 或者 false）

>Boolean 对象
您可以将 Boolean 对象理解为一个产生逻辑值的对象包装器。
Boolean（逻辑）对象用于将非逻辑值转换为逻辑值（true 或者 false）。

```js
注释：如果逻辑对象无初始值或者其值为 0、-0、null、""、false、undefined 或者 NaN，
那么对象的值为 false。否则，其值为 true（即使当自变量为字符串 "false" 时）！
var myBoolean=new Boolean();
var myBoolean=new Boolean(0);
var myBoolean=new Boolean(null);
var myBoolean=new Boolean("");
var myBoolean=new Boolean(false);
var myBoolean=new Boolean(NaN);

```
