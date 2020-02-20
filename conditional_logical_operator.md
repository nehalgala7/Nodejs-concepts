# Condtional and Logical operators

## Overview
 
Conditional and logical operators are used in decision-making statements, which determine the path of execution based on the condition specified as a combination of multiple Boolean expressions. 

A critical requirement of every conditional is the condition. The condition is what determines the decision to be made in the program.

In JavaScript, this condition can be any valid expression. Usually, this condition expression, however complex it is, is evaluated to one of two values called booleans: either true or false.

A proper understanding of how the JavaScript engine converts these condition expressions to booleans is necessary for writing correct and predictable conditional logic.

Identifying truthy and falsy values fundamental concept that can enable us to understand the conversions - 
Every value in JavaScript can be classified as either truthy or falsy. The falsy values in JavaScript are as follows:

```
'' or "" or ``(an empty string)
0 or -0 (the number 0)
null
undefined
NaN
false
```
Every other value besides the ones in this list are truthy values. Whenever JavaScript expects a boolean value, truthy values are implicitly coerced to true while falsy values are implicitly coerced to false.

### Prerequisite
Learn about [Comparison operators in javascript](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Comparison_Operators)

## Learning Outcome

- What are conditional operators?
- What are logical operators?
- How to use them together to decide the flow control of a program?


## Introduction

### Conditional Operators

Sometimes, we need to perform different actions based on different conditions. For this we use condtional operators. There are different types of conditionals operators in javascript. Click on each on of them to read in depth about it.

1. [If](https://www.geeksforgeeks.org/else-statement-javascript/#if)  conditional operator
2. [if - else](https://www.geeksforgeeks.org/else-statement-javascript/#if-else)  conditional operator 
3. [if - else if - else](https://www.geeksforgeeks.org/else-statement-javascript/#if-else-if)  conditional operator
4. [Ternary operator](https://www.javascripttutorial.net/javascript-ternary-operator/)

#### what must you do
- 
- Read and [Solve excerices related to conditional operators](https://javascript.info/ifelse#boolean-conversion)

### Logical Operators


#### what must you do

- Read more about how to [create and initialize variables in javascript](https://www.w3schools.com/js/js_variables.asp)
- Read about [different data types in javascript](https://javascript.info/types) and also solve the excerises given there. Deep dive into [Types & Data Structures Basics](https://codeburst.io/javascript-essentials-types-data-structures-3ac039f9877b).
- In JavaScript variable have scope. Scoping is nothing but accessibility of a variable withing a program. Read [Scope of a variable](https://scotch.io/tutorials/understanding-scope-in-javascript).
- In JavaScript, there is a concept of hoisting which is associated with scoping. Hoisting is the default behavior of moving all the declarations at the top of the scope before code execution. Basically, it gives us an advantage that no matter where functions and variables are declared, they are moved to the top of their scope regardless of whether their scope is global or local. Read in depth about [variable scope](http://javascriptissexy.com/javascript-variable-scope-and-hoisting-explained/).

## Additional Resources

- This article gives an overview about about [Javascript works](https://blog.sessionstack.com/how-does-javascript-actually-work-part-1-b0bacc073cf) and if you want to go a little deeper into [How JavaScript works differently in browser and node](https://itnext.io/how-javascript-works-in-browser-and-node-ab7d0d09ac2f)

- This chapter discusses JavaScript's basic grammar, variable declarations, data types and literals. Dive deeper into the [JS Grammar](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Grammar_and_Types)


