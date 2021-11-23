轉換數值類型 --> String
使用

```
var a = 123
//
a.toString();
console.log(typeof a)
--> Still Number
```
數值已經被轉換了，但原變數 a 是不會改變的
改變的是 "123" 而不是 a, 
故：

```
var a = 123;
a.toString();
var b = a.toString();
或者
a = a.toString();
console.log(typeof a)
---> String 
```

L11
Null & Undifined 沒有 toString 方法，若用到會報錯。
也可以用
```
a = String(a);
```
將變數轉為String

Number & Boolean 用 String(); 是ＯＫ的
但如果遇到 null & undifined 就會變成單純 String : "null" & "undifined"
