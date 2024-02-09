**Reading Notes | 8 FEB 2024**

# Class 008

Read: 08 - Operators and Loops

### **Notes Outline**  
**Expressions**  
At a high level, an expression is a valid unit of code that resolves to a value. There are two types of expressions: those that have side effects (such as assigning values) and those that purely evaluate.

The expression x = 7 is an example of the first type. This expression uses the = operator to assign the value seven to the variable x. The expression itself evaluates to 7.  

In JavaScript, an expression is a combination of values, variables, operators, and functions that evaluates to a single value. It could be a simple value like a number or a string, a reference to a variable, or a more complex combination of these elements.

For example:

5 is a simple numeric expression.
x + 2 is an expression that adds the value of variable x to 2.
myFunction() is an expression that calls a function named myFunction.
true && (x > 5) is a complex expression involving logical and relational operators.
Essentially, if you can write it and it returns a value, it's likely an expression.

Loops:  
Top Down
**Assignment Operators:**  
An assignment operator assigns a value to its left operand based on the value of its right operand. The simple assignment operator is equal (=), which assigns the value of its right operand to its left operand. That is, x = f() is an assignment expression that assigns the value of f() to x.

**Comparison Operators:**  
A comparison operator compares its operands and returns a logical value based on whether the comparison is true. The operands can be numerical, string, logical, or object values. Strings are compared based on standard lexicographical ordering, using Unicode values.  

>const var1 = 3;  
const var2 = 4;  






### **Questions & Answers:**  

1. **What is an expression in JavaScript?**
An expression is a combination of values, variables, operators, and functions that evaluates to a single value.  

2. **Why would we use a loop in our code?**  
Loops are used in JavaScript (and in programming in general) to execute a block of code repeatedly. They are extremely useful when you need to perform a task multiple times or when you need to iterate over a collection of data.  

3. **When does a for loop stop executing?**  
A for loop stops executing when the condition specified in its control statement evaluates to false.  

4. **How many times will a while loop execute?**  
A while loop will execute as long as its condition evaluates to true. There's no predefined limit to the number of times a while loop will execute, unlike a for loop where you specify the number of iterations explicitly. Instead, the loop will continue to execute until the condition becomes false.  

