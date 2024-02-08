# **Reading Notes | 8 FEB 2024**

# Class 007

Read: 07 - Programming with JavaScript

*Bookmark:*

### **Notes Outline** 

**Javascript Functions:**

1. Stay in rythm
    - Teach topic x. Read topic x. Practice topic x.  

A JavaScript function is a block of code designed to perform a particular task.  

A JavaScript function is executed when "something" invokes it (calls it).  

A JavaScript function is defined with the function keyword, followed by a name, followed by parentheses ().  
Function names can contain letters, digits, underscores, and dollar signs (same rules as variables).  
The parentheses may include parameter names separated by commas: (parameter1, parameter2, ...)  
  
>function name(parameter1, parameter2, parameter3) {
  // code to be executed
}  
The code to be executed, by the function, is placed inside curly brackets: {}  

**The () Operator:**  
The () operator invokes (calls) the function:

>function toCelsius(fahrenheit)  
{
  return (5/9) * (fahrenheit-32);
}
>let value = toCelsius(77);
(key is to add the values)

**Control Flow:**  
The *control flow* is the order in which the computer executes statements in a script.
Control flow means that when you read a script, you must not only read from start to finish but also look at program structure and how it affects order of execution.  

### **Questions & Answers:**

1. **What is control flow?**  
Control flow refers to the order in which the instructions within a program are executed. It determines the path the program takes based on conditions and decisions made during execution. Essentially, control flow governs the flow of execution through the code, determining which statements are executed next based on the logic and conditions specified in the program.  

2. **What is a Javascript Function?**  
A JavaScript function is a block of reusable code that performs a specific task or calculates a value. Functions are one of the fundamental building blocks of JavaScript programming and are used to organize code, make it more modular, and promote code reuse.  

3. **What does it mean to invoke - or call - a function?**  
Invoking or calling a function in JavaScript means executing the code within the function's body. When you invoke a function, you're telling JavaScript to run the instructions defined within that function.

4. **What are the parenthesis () for when you define a function?**  
In JavaScript, parentheses () are used when defining a function to enclose the parameters that the function accepts. These parameters represent placeholders for values that can be passed into the function when it is called.
