# Condtional and Logical operators

## Overview
 
Conditional and logical operators are used in decision-making statements, which determine the path of execution based on the condition specified as a combination of multiple Boolean expressions. 

A critical requirement of every conditional is the condition. The condition is what determines the decision to be made in the program.

In JavaScript, this condition can be any valid expression. Usually, this condition expression, however complex it is, is evaluated to one of two values called booleans: either true or false.

A proper understanding of how the JavaScript engine converts these condition expressions to booleans is necessary for writing correct and predictable conditional logic.

Identifying truthy and falsy values fundamental concept that can enable us to understand the conversions:
Identifying truthy and falsy values in javascipt - 
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

Sometimes, we need to perform different actions based on different conditions. For this we use condtional operators. There are different types of conditionals operators in javascript.

1. If  conditional operator
2. if - else  conditional operator 
3. if - else if - else  conditional operator
4. Ternary operator

#### what must you do
- 
- Read and [Solve excerices related to conditional operators](https://javascript.info/ifelse#boolean-conversion)

### Logical Operators


#### what must you do

- Read more about how to [create and initialize variables in javascript](https://www.w3schools.com/js/js_variables.asp)
- Read about [different data types in javascript](https://javascript.info/types) and also solve the excerises given there. Deep dive into [Types & Data Structures Basics](https://codeburst.io/javascript-essentials-types-data-structures-3ac039f9877b).
- In JavaScript variable have scope. Scoping is nothing but accessibility of a variable withing a program. Read [Scope of a variable](https://scotch.io/tutorials/understanding-scope-in-javascript).
- In JavaScript, there is a concept of hoisting which is associated with scoping. Hoisting is the default behavior of moving all the declarations at the top of the scope before code execution. Basically, it gives us an advantage that no matter where functions and variables are declared, they are moved to the top of their scope regardless of whether their scope is global or local. Read in depth about [variable scope](http://javascriptissexy.com/javascript-variable-scope-and-hoisting-explained/).

### Type conversions
#### What is type conversion?
Typecasting or coercion in simple term means to change the data type of a value to to another data type like for example, number to a string or a string to a boolean etc.


JavaScript is loosely typed language and most of the time operators automatically convert a value to the right type but there are also cases when we need to explicitly do type conversions.

There are two types of coercion, implicit and explicit. Implicit coercion is when there is automatic conversion of data type, where as When a developer expresses the intention to convert between types by writing the appropriate code, it’s called explicit type coercion (or type casting).

JavaScript only supports three type of conversion
1. to string - We can explicitly convert values to a string using the String() method .
   ```
   var val = 5;
   String(val); //explicit coercion
   ```
   
   Also JavaScript does a implicit string coercion when used with the + operator. The most trivial example would be            concatenation.
   
   ```
   '10' + val; //105 not 15 and o/p is a String, implicit coercion 
   ```
   Note: All other primitive values(string, number, boolean) are converted to string naturally
   
2. to boolean
3. to number

You can read in depth about these three type of conversions here [types of conversions](https://www.oreilly.com/library/view/you-dont-know/9781491905159/ch04.html). It has plenty of examples to help to understand the concept thoroughly 


#### what must you do
- Go through this detailed blogpost on [Type Conversions in JS](https://www.dyn-web.com/javascript/type/)
- Try to solve the excerices given in the following post [Examples of Type Conversions](https://javascript.info/type-conversions) and 


## Additional Resources

- This article gives an overview about about [Javascript works](https://blog.sessionstack.com/how-does-javascript-actually-work-part-1-b0bacc073cf) and if you want to go a little deeper into [How JavaScript works differently in browser and node](https://itnext.io/how-javascript-works-in-browser-and-node-ab7d0d09ac2f)

- This chapter discusses JavaScript's basic grammar, variable declarations, data types and literals. Dive deeper into the [JS Grammar](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Grammar_and_Types)



