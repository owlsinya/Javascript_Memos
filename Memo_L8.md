Lesson 8:

var 僅需定義一次，之後就不必再var 來定義同一個變數
```
var str2 = "hello";

str2 = "adios";
```

若想知道數值的類型，可用```typrof``` 來檢查
```
var a = 123;
var b = "123";

console.log(typeof a);

```
如果算出來非數字
```
var a = "abc" * "def"
console.log(a) 

---會顯示---
NaN
```
如果使用JS做小數（浮點數）計算，可能會得到不精確的結果（因為二進位無法表示1/10)
因此不要用JS做精確度要求高的運算。
