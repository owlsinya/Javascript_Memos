# Spread Operator
 
也就是常見的

```
[...array] 的 ... 
```
其作用相當多
就是分開陣列（array) 中的每個數值 (Value)？
例如可用在複製 array 上

```
var arr = [1, 2, 3];
var arr2 = [...arr];
arr.push(4);
console.log(arr); -> [1, 2, 3]
console.log(arr2); -> [1, 2, 3, 4]
```

![教學影片](https://www.youtube.com/watch?v=iLx4ma8ZqvQ)
