# Dynamic Web Pages with JavaScript

# What is JavaScript?

If HTML is the skeleton, and CSS is the skin, Javascript are the muscles. JavaScript allows users to interact with the site and make it do things, and allows programmers to have the website make the users interact with it.

# Variables

What are variables? Well, they are basically just labels given to a container that stores data. Creating a variable in JavaScript is called **declaring**. This is done with the command `var`, `let` or `const`. After the command, you need to give the variable a name (preceded by a space), which is called the **identifer**.

## Identifier Naming Convention
* `$` and `_` are considered letters in JavaScript
* They can contain letters and digits
* They are case sensitive
* Reserved words cannot be used as names
* Camel case is the industry standard (ex: camelCase)

## The Assignment Operator

In JavaScript, `=` is not what we thing of in math as "equal to;" it is known as an assignment operator. If you declare a variable, but don't use the assignment operator and give it a value, the variable is `undefined`. As you can see in the following example, the first variable is `undefined` and the one has a value of 10 (note that you also have to follow declarations with a semi-colon):

>let x;
>
>let y = 8 + 2

## JavaScript Data Types

JavaScript variables can hold number values and text values. Text values are called **text strings** in programming. Strings are put in quotes and numbers are not. A number will be treated as a text string if you put it in quotes. As you saw in the example above, you can assign a value by doing math. If you add text strings to create a value, they will be concatenated (aka no space).
