## 屬性宣告與連結

#### APP.js

```
import logo from './logo.svg';
import './App.css';
import { Greet } from './components/Greet';
import Welcome from './components/Welcome';
import Hello from './components/Hello';


function App() {
  return (
    <div className="App">
     <Greet name = "Bruce" heroName = "Batman"/>
     <Greet name = "Clark" heroName = "Superman"/>
     <Greet name = "Diana" heroName = "Wonder Woman"/>
  
    </div>
  );
}

export default App;
```
### 在Greet.js呼叫後加入新參數，需要回Greet內提供相對應的顯示語法
#### Greet.js  

{props.#} 用來呼叫相對應的參數
```
import React from "react";

// function Greet(){
// 	return <h1>HELLO Vishwas</h1>
// }

export const Greet = (props) => {
console.log(props)
return <h1>Hello {props.name} a.k.a {props.heroName}</h1>
}
export default Greet!
```
Result：  

![](https://user-images.githubusercontent.com/37833642/145333610-c90380f6-aeb5-45af-a540-bc5ea7347f86.png)

