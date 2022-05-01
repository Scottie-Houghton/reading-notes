# Programming with JavaScript

# JavaScript Functions

A JavaScript function is a block of code designed to perform a particular task. The code inside a JavaScript function is not executed until it is called to. In programming, the verb **invoke** is used to describe this. Functions are useful because you can reuse the code without entering it over and over again. Since you can reuse it, you can also use it with different arguments, to produce different results.

# JavaScript Function Syntax

To create a function, you start out with the command `function`, then a space and then you're going to give it a name (just like a variable) followed by parentheses `()`. What are called **parameters** can be put in the parentheses; they can be given value, called **arguments** when the function is invoked. Finally, the code to be executed by the function is surrounded by curly brackets `{}`. Any variables declared within a function are local to the function and only be accessed within it. The only way something can leave a function is with a `return` command. A function stops executing when it reaches a return statement.

# Invoking a Function and Using it as a Variable Value

A function can only be invoked when its parentheses `()` are also included in the invocation. A lot of the time when a function is invoked, it is used as a value of a variable. Here is a great example of a function and then it being used as a variable value:

>function toCelsius(fahrenheit) {
>
>    return (5/9) * (fahrenheit-32);
>
>}
>
>
>let x = toCelsius(77);
>
>let text = "The temperature is " + x + " Celsius";