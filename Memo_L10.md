轉換數值類型
使用

```
var a = 123
//
a.toString();
console.log(typeof a)
--> Still Number
```
數值已經被轉換了，但原變數是不會改變的
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

