#### Callback Functions

* Callback functions are arguments that are passed into functions and then later executed within the function. In the real world you can can think as a cook as a callback function to the waiter that helps you at your table. When the waiter recieves an order of food, the waiter calls upon the cook and passes the order of food recieved to the cook.

```javascript

    function waiterGetsFood(order, cook) {
        console.log("Waiter recieves order and heads to kitchen");
        cook(order);
    }
    function cook(order) {
        return "Cook has finished cooking " + order;
    }
```

#### Closure

* Closures are inner functions that retain access to the parent wrapping function's local scope. As long as the returned inner function is alive in memory the local scope of the outer function will continue to have access to manipulate and retrieve the values of the variables.

#### arguments

* The `arguments` keyword is a keyword that exists on every function scope, it is an array that contains every argument passed in. It is usually used to write functions definitions that allow for a variable of arguments not predefined. 

#### Recursion

* Recursion is the process of a function continously involking itself, a base case is required to tell the function to stop calling itself. Recursive functions usually use the previous return value of the function in it's next recursive call.

#### prototype

* The `prototype` property exists on every javascript object. It's an object that contains properties and methods that are available to every instance of that object type.

#### Constructors

* Constructors are functions that are used to create objects, within these functions you set properties methods to the `this` keyword which in turn creates a new object with those properties and methods. These new objects are called an `instance`.

