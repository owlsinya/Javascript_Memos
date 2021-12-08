# REACT 筆記01
### 建立REACT APP
[Create React App](https://reactjs.org/docs/create-a-new-react-app.html#create-react-app)

建議用 VS CODE 編輯


### 宣告方式 
App.js
```
import logo from './logo.svg';
import './App.css';
import { Greet } from './components/Greet'; 
>> 如果Greet內有宣告 export default Greet，名字可以自取。

function App() {
  return (
    <div className="App">
     <Greet />
    </div>
  );
}

export default App;
```

Greet.js
```
import React from "react";

// function Greet(){
// 	return <h1>HELLO Vishwas</h1>
// }

export const Greet = () => <h1>Hello Vishwas</h1>

export default Greet
```
