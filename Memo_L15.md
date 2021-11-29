typeof()方法所產出的值以String返回儲存

```
var a = 123;
var result = typeof a;
console.log(typeof resulf);
--> "String"
```
加減乘除在code中，會將不同類型（number/String/boolean...等）轉換回number來運算
```
result = 456 + 789
result = true + 1 (=2)
result = true + false (=1)
result = 2 + null = (=2)
```
任何數值與 NaN 做運算都會得出 NaN
```
result = 2 + NaN = NaN
```
String相加不會轉為Number運算，會直接將字串相加
```
result = "帥哥“ + "你的奶茶" = "帥哥你的奶茶"
```
