將數值轉換為 Number

轉換方式一：
```
Number()函數

```
範例
```
var a = "123";
Number();
>> a = Number(a);
```
Number()
1. 只能將數字的字串轉換成數字
2. 有非數字的內容，則轉換成Nan
3. 如果 a 是空格，則轉換為 0 

----

轉換方式二：
1. 這個函數專門用在String上
2. parseInt()能把字串轉為整數
3. parseFloat()能轉為浮點數
4. 僅將有效的整數取出來轉換

範例
```
var a = "123px";
parse() > 
a = parseInt(a);
console.log(typeof a) > number
console.log(a) > 123
```
