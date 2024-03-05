## Prep: Things I Want To Know More About

## 19 FEB 2024  

What is the VSCode GoLive extension?  

    Starts a unique server (1. A computer, 2. An app: job is to pull the file on the machine and give to the browser requesting.)  
  
What is the difference between Git Checkout and Git Switch?

## 20 FEB 2024  

Where does my code go?  
Environment: Place where the code runs  
EX: Browser is a environment, VSCode is a environment

*.files* are hidden in the terminal. To view these hidden files, we use the ls -a or the ls -al commands to either reveal all files or reveal all files in long format.  
  
## 26 FEB 2024  

JavaSCript: math.random  

In JavaScript, Math.random() is a built-in function that generates a pseudo-random floating-point number between 0 (inclusive) and 1 (exclusive). It returns a random number in the range \[0, 1), meaning it can return 0 but will never return 1.

        function getRandomNumberBetween(min,max)
            return Math.floor(Math.random() * (max-min+1) + min);

In JavaScript, Math.floor() is a built-in function that returns the largest integer less than or equal to a given number. It essentially rounds down a number to the nearest integer.

### DOM: The DOCUMENT OBJECT MODEL  

Browser: "Brings the document to life."

    1. Reads the HTML
    2. Renders it
    3. Executes the JavaScript
    4. Applies CSS styles  

Coders have access to:  
    1. modify parts of the page (add/remove)  
    2. Inspect elements oe any property.
  
## 27 FEB 2024  

### Explain prototypes and inheritance via an analogy from your previous work experience

### Writing JavaSCript Code

Keep it clean and ordered.

 1. Declare your variables.  
 2. Write your functions
 3. Use conditional statements.
 4. Use loops.
 5. Call the function tu run.
  
## 27 FEB 2024

In JavaScript, a prototype method is a method that is shared among all instances of a constructor function. When you create a constructor function and use the prototype property to define a method, that method becomes accessible to all objects created with that constructor function.

Constructor Function: This is a function used to create objects with a specific structure. It typically initializes properties and methods that will be common to all instances created from it.

Prototype Property: Every function in JavaScript has a special property called prototype. This property allows you to add properties and methods to all objects created with that function as a constructor.

Prototype Method: When you add a method to the prototype property of a constructor function, that method becomes available to all instances created from that constructor. This allows you to define methods that are shared among all instances, rather than creating a separate function for each instance.

## 4 MARCH 2024  

Audio & Video:  
\<figure> is the appropriate semantic to embed both audio and video. 

CSS GRID: 

CSS Grid is a powerful layout system that allows developers to create complex web layouts with ease. Here are some key concepts to understand:

    Grid Container: This is an element that contains grid items. You can designate any element as a grid container by setting its display property to grid or inline-grid.

    Grid Items: These are the children of the grid container that participate in the grid layout. They are positioned within the grid using grid lines and grid tracks.

    Grid Lines: These are the horizontal and vertical lines that form the grid. Grid lines separate the rows and columns of the grid.

    Grid Tracks: These are the spaces between the grid lines. You can think of them as the rows and columns of the grid. Grid tracks can be explicitly defined with size values (such as pixels or percentages) or automatically generated.

    Grid Areas: These are rectangular areas within the grid layout that contain one or more grid items. You can define named grid areas using the grid-template-areas property.

    Grid Template: This is a shorthand property that allows you to define the structure of the grid in terms of rows, columns, and grid areas. You can specify the size and alignment of grid tracks, as well as the placement of grid items.

    Grid Line Numbers: Grid lines are numbered starting from 1. Negative line numbers count from the end of the grid.

    Grid Placement: Grid items can be placed onto the grid using various properties like grid-row, grid-column, grid-area, etc.

    Grid Spanning: Grid items can span multiple rows and/or columns using the grid-row and grid-column properties.

    Alignment: CSS Grid provides powerful alignment capabilities for both grid items and the grid itself. You can align items within individual grid cells, as well as align the entire grid within its container.
