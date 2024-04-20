# Welcome to React-handler!

Hi! I'm your first Markdown file in **cs-react-handler**.



**

# npm install dependencies

**

    npm install csx-react-handler
This command line helps to install react-handler.

**

# Components

**
1)Button
2)Counter
and many more components will be adding soon.


**

# Code

**

    import { useCounter,Button } from  "csx-react-handle";

    import  React  from  "react";
    const  Counter  = () =>{
	    const { count, increment, decrement} =  useCounter();
	    return  <div>
		    <Button  onClick={increment}>+</Button>
		    <h1>{count}</h1>
		    <button  onClick={decrement}>-</button>
		</div>;
    }
    export  default  Counter;

