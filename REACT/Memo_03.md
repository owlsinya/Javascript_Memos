## 繼承數值

### APP.js
```
import logo from './logo.svg';
import './App.css';
import { Greet } from './components/Greet';
import Welcome from './components/Welcome';
import Hello from './components/Hello';


function App() {
  return (
    <div className="App">
     <Greet name = "Bruce" heroName = "Batman">
        <p>This is children prop</p>
      </Greet>
     <Greet name = "Clark" heroName = "Superman">
       <button>Action</button>
       </Greet>
     <Greet name = "Diana" heroName = "Wonder Woman"/>
     <Welcome name = "Bruce" heroName = "Batman"/>
     <Welcome name = "Clark" heroName = "Superman"/>
     <Welcome name = "Diana" heroName = "Wonder Woman"/>
    </div>
  );
}

export default App;
```
＊children 屬於 prop 下的語法  

用 this 語法來繼承不同js之間的數值. 

### Welcome.js
```
import React, { Component } from "react";

class Welcome extends Component{
	render(){
		return <h1>Welcome {this.props.name} a.k.a {this.props.heroName}</h1>
	}
}

export default Welcome
```
#### Result:

![](https://user-images.githubusercontent.com/37833642/145344718-2fa59be0-1edb-4231-8fd9-1c8c3b4924f1.png)


