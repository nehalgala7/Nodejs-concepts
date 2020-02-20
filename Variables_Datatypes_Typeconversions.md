# Variables, Data types, Type conversions

## Overview
 
In this concept, we will help you understand about the basic building blocks of JavaScript i.e variables and all the topics related to it - data types and type conversions.

You'll be writing a program to find the largest and the smallest number from a list once we have covered all the topics under the section - Basic Javascript.

For now, after this concept you'd be able to declare a variable and initialize it with one of the basic data type.


## Learning Outcome

- What is a variable?
- How to create a variable, store, modify the value in a varaiable, and use it in a program?
- What is a data type and what are the basic data types supported in Javascript?
- How type conversions work in javascript


## Introduction

### Variables in JS

The variable is one of the most fundamental concepts in any programming language. It is the basic unit of storage in a program. A variable is a way to store information so that you can later use it.

JavaScript variables were solely declared using the var keyword followed by the name of the variable and semi-colon. Below is the syntax to create variables in JavaScript:

```
var var_name;
var x;
```

The var_name is the name of the variable which should be defined by the user and should be unique. There are rules one must adhere to while defining a varaible. You can read more about it here  [Naming variable javascript](https://www.dummies.com/web-design-development/javascript/naming-javascript-variables/)

![Variables](https://scotch-res.cloudinary.com/image/upload/dpr_2,w_800,q_auto:good,f_auto/media/8976/bNTL1QI3RFebh7C1JPYC_variable%20hoisting.png)

### Data types 

Data type is nothing but type of information.
JavaScript includes data types similar to other programming languages like Java or C#. Data type indicates characteristics of data. It tells the compiler whether the data value is numeric, alphabetic, date etc., so that it can perform the appropriate operation.

JavaScript has six primitive data types:

1. null
2. undefined
3. boolean
4. number
5. string
6. symbol – available only from ES6
and one complex data type called object.

#### what must you do

- Read more about how to [create and initialize variables in javascript](https://www.w3schools.com/js/js_variables.asp)
- Read about [different data types in javascript](https://javascript.info/types) and also solve the excerises given there. Deep dive into [Types & Data Structures Basics](https://codeburst.io/javascript-essentials-types-data-structures-3ac039f9877b).
- In JavaScript variable have scope. Scoping is nothing but accessibility of a variable withing a program. Read [Scope of a variable](https://scotch.io/tutorials/understanding-scope-in-javascript).
- In JavaScript, there is a concept of hoisting which is associated with scoping. Hoisting is the default behavior of moving all the declarations at the top of the scope before code execution. Basically, it gives us an advantage that no matter where functions and variables are declared, they are moved to the top of their scope regardless of whether their scope is global or local. Read in depth about [variable scope](http://javascriptissexy.com/javascript-variable-scope-and-hoisting-explained/).

### Type conversions


#### what must you do
- Go through this detailed blogpost on [Type Conversions in JS](https://www.dyn-web.com/javascript/type/)
- Try to solve the excerices given in the following post [Examples of Type Conversions](https://javascript.info/type-conversions) and 


## Additional Resources

- This article gives an overview about about [Javascript works](https://blog.sessionstack.com/how-does-javascript-actually-work-part-1-b0bacc073cf) and if you want to go a little deeper into [How JavaScript works differently in browser and node](https://itnext.io/how-javascript-works-in-browser-and-node-ab7d0d09ac2f)

- This chapter discusses JavaScript's basic grammar, variable declarations, data types and literals. Dive deeper into the [JS Grammar](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Grammar_and_Types)


