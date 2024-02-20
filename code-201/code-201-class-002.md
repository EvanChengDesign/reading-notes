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
