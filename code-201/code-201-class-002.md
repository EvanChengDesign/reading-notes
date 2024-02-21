# **Reading Notes | 20 FEB 2024**

# Class 002  
  
## Readings: Basics of HTML, CSS & JS  

### *Bookmarks:*

[How to Write a Git Commit Message](https://cbea.ms/git-commit/)

### **Notes Outline:**

let: allows variable to change.  
ex: let wife = "Cathy";
wife = "Cathy"  

const: variable will never change.  
ex: wife = "null" (ERROR will happen because the value has to equal the CONST)  
  
== & === are comparisons  
comparators return a boolean (true/false)  

Switch Statements:  

    switch(firstCharacter) {  

    case "y":
        console.log("good!");
        break ; (break out of code block if statement is met)
    case "n":
        console.log("Um...you can still type?");
        break;
    default: 
        console.log("What?");
        break;
    }
Array:  
A List of variables  
Beware of the "off by 1 errors"  
use >, don't use >=

    Let wife = "cathy"
  
    ex: Let people = ["John", "John", "Zach", wife];

Iterate:

To iterate over an array in JavaScript means to sequentially access each element of the array and perform some operation on it. Iteration allows you to loop through each item in the array, accessing its value and index, and potentially performing some action or computation with each element.

    ex: let pets = ["Rosie", "Geno", "Rocky"];
        for( let i = 0; i< pets.length; i++ ) {
            console.log( pets[i].toUpperCase() );
        }

    Console Output: 
    ROSIE
    GENO
    ROCKY

    The function iterates for each item in the array and converts the strings within to all uppercase. 

### **Questions & Answers**  

**Why is it important to use semantic elements in our HTML?**  
Semantic elements are conducive to higher accessibility ratings.  

**How many levels of headings are there in HTML?**  
There are six heading elements. from h1 to h6.  

**What are some uses for the \<sup> and \<sub> elements?**  
These elements are used for superscript and subscript marking up.  

**When using the \<abbr> element, what attribute must be added to provide the full expansion of the term?**
If providing the expansion in addition to the abbreviation makes little sense, and the abbreviation or acronym is a fairly shortened term, provide the full expansion of the term as the value of title attribute:  
**What are ways we can apply CSS to our HTML?**  
There are several ways to apply CSS styles to HTML elements:  

1. Inline Styles  
2. Internal Stylesheets
3. External Stylesheets
4. CSS Frameworks

**Why should we avoid using inline styles?**  
While inline styles can be convenient for quickly applying styles to individual HTML elements, they are generally considered poor practice for several reasons. These include maintainability, readability, specificity, and separation of concerns.

**What is representing the selector?**  

      h2  

**Which components are the CSS declarations?**  

      color & padding

**Which components are considered properties?**  

      black and 5px 
**What data type is a sequence of text enclosed in single quote marks?**  
A sequence of text enclosed in single quote marks in JavaScript represents a string data type. Strings in JavaScript are used to store and manipulate textual data, such as words, sentences, or any sequence of characters. Here's an example:

**List 4 types of JavaScript operators.**

1. Assignment: let x = 10;
2. Logical: let isTrue = true && false; Logical  
3. Comparison: letEqual = 10 === 5; Equal to (strict equality)
4. Arithmetic: let result = 10 + 5; Addition

**Describe a real world problem you could solve with a Function.**  
A real-world problem that could be solved with a function is calculating the total cost of items in a shopping cart.

Let's say you're developing a website, and you need to implement a feature that calculates the total cost of items in a user's shopping cart. You can create a function to handle this task that utilizes arrays and a for statement, to return the total cost.

**An if statement checks a __ and if it evaluates to ___, then the code block will execute.**  
The statement checks a condition and evaluates true or false, based on whether the condition is true or false, respectively.

**What is the use of an else if?**  
The else if statement follows an if statement and must come before the else statement. It introduces a new condition to test if the previous if statements condition is false.

    let x = 10;

    if (x > 10) {
    console.log("x is greater than 10");
    } else if (x === 10) {
    console.log("x is equal to 10");
    } else {
    console.log("x is less than 10");
    }If x is greater than 10, the message "x is greater than 10" is logged. 

    If x is equal to 10, the message "x is equal to 10" is logged.  

    If neither of the above conditions is true (i.e., if x is less than 10), the message "x is less than 10" is logged.  

**List 3 different types of comparison operators.**  
    1. Equal to: '==' or '==='  
    2. Not equal to: '!=' or '!==' (checks value and type)  
    3. Greater than: '>'
  
**What is the difference between the logical operators (&& and ||)?**  
The logical operators (logical OR) are used to combine multiple conditions in JavaScript. They differ in how they evaluate expressions and return a result:

The (&&) operator returns true if both operands are true, and false otherwise.  
The (||) operator returns true if at least one of the operands is true, and false otherwise.
