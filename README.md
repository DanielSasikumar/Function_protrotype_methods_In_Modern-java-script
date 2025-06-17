🧠 JavaScript Function Prototype Methods – call(), apply(), and bind()
This code demonstrates how JavaScript’s core function methods—call(), apply(), and bind()—can be used to control function invocation and argument passing.

Function Constructor: Shows how to create a function dynamically using the Function constructor (though in this case, the function body is empty).

call(): Invokes a function by passing arguments individually. Useful for setting the this context explicitly.

apply(): Similar to call(), but accepts arguments as an array. Commonly used to work with functions like Math.max() and Math.min() when you have an array of values.

bind(): Returns a new function with a bound this context and optional preset arguments. In this example, it's used to pre-bind an array of numbers to Math.max() and execute it later.

Also included:

Finding the min and max values in an array using Math.min()/Math.max() with apply().

Example usage of bind() to create reusable functions with preset arguments.

This code helps understand how function context and arguments can be manipulated for more flexible and reusable JavaScript functions.

