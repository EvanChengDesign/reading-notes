# **Reading Notes | 21 FEB 2024**

# Class 003

## *Readings: HTML Lists, Control Flow with JS, and the CSS Box Model*

## **Notes Outline:**  

## **Questions & Answers**  

### **When should you use an unordered list in your HTML document?**  

Use an unordered list (\<ul>) in your HTML document when you have a list of items that don't need to be in a specific order, such as a list of bullet points or a navigation menu.

### **How do you change the bullet style of unordered list items?**  

You can change the bullet style of unordered list items using CSS. Set the list-style-type property to specify different bullet styles like disc, circle, or square.

### **When should you use an ordered list vs an unorder list in your HTML document?**  

Use an ordered list (\<ol>) when the items in your list need to be in a specific order, such as steps in a process or ranked items.

### **Describe two ways you can change the numbers on list items provided by an ordered list?**  

Two ways to change the numbers on list items provided by an ordered list:

* Use the type attribute to specify the type of numbering, such as "1" for numeric numbering, "A" for uppercase alphabetical numbering, or "a" for lowercase alphabetical numbering.  

* Use CSS to style the numbering. You can change the color, size, or style of the numbers using properties like color, font-size, or list-style.
  
### **Describe the CSS properties of margin and padding as characters in a story. What is their role in a story titled: “The Box Model”?**  

Once upon a time in the enchanted land of CSS, there existed two characters named Margin and Padding. Margin was a friendly and outgoing character, always eager to create space and maintain harmony between elements. Padding, on the other hand, was more reserved and introspective, finding solace in providing comfort and support to the content within.  

Margin, with its generous spirit, acted as a buffer between neighboring elements, ensuring that they had ample breathing room and did not encroach upon each other's territories. Margin's role was to maintain order and prevent elements from crowding each other, allowing each one to stand out and shine in its own right.

Meanwhile, Padding, with its nurturing nature, enveloped the content within each element with tender care and protection. Padding offered a cozy sanctuary for the content, shielding it from the harsh exterior world and providing a soft cushion against the rigors of the digital realm. Padding's role was to enhance the user experience, ensuring that the content was presented in a visually appealing and comfortable manner.

### **List and describe the four parts of an HTML elements box as referred to by the box model.**  

    1. Margin  
    2. Border  
    3. Padding  
    4. Content  

### **What data types can you store inside of an Array?**  

You can store numerous amounts of data types in an array. Some of these include:

    1. numbers  
    2. strings  
    3. objects  
    4. arrays
    5. booleans
    6. functions

### **Is the people array a valid JavaScript array? If so, how can I access the values stored? If not, why?**  

Yes, that is a valid array in JavaScript. It's a two-dimensional array, also known as an array of arrays. Each inner array represents information about a person, containing elements such as name, age, occupation, and hobbies.  
  
  To access the values stored in the two-dimensional array people, you can use array indexing. Since people is an array of arrays, you'll use two sets of square brackets to access specific elements.

### **List five shorthand operators for assignment in javascript and describe what they do.**  

    +=: this operator adds the value on the right to the variable on the left and assigns the result to the variable.  
      
    -+: it subtracts the value on the right from the variable on the left and assigns the result to the variable.  

    *=: This operator multiplies the variable on the left by the value on the right and assigns the result to the variable.  

    /=: It divides the variable on the left by the value on the right and assigns the result to the variable.  

    %=: This operator divides the variable on the left by the value on the right and assigns the remainder to the variable.     

### **Read the code below and evaluate the last expression and explain what the result would be and why.**  

### **Describe a real world example of when a conditional statement should be used in a JavaScript program.**  

A common real-world example of when a conditional statement should be used in a JavaScript program is in a login system. Consider a website where users need to enter their username and password to access certain features or content. In such a scenario, a conditional statement can be used to verify whether the entered username and password match those stored in the system's database.

### **Give an example of when a Loop is useful in JavaScript.**  

A common scenario where a loop is useful in JavaScript is when dealing with arrays or lists of data. For instance, consider a situation where you want to calculate the total price of items in a shopping cart. Instead of manually adding each item's price, you can use a loop to iterate over the items in the cart and accumulate their prices.
