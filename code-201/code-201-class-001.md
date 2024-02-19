# **Reading Notes | 19 FEB 2024**

# Class 001

### *Bookmarks:*

[How The Web Works](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/How_the_Web_works)  

[Website & Design](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/What_will_your_website_look_like)  

### **Notes Outline:**  

**Getting Started:**  

JavaScript is a programming language that adds interactivity to your website. If HTML is the blueprint and CSS the styling, JavaScript is the functionality. Javascript functions are triggered in numerous ways. This happens in games, in the behavior of responses when buttons are pressed or with data entry on forms; with dynamic styling; with animation, etc.  

## **Questions & Answers:**  

1. Compose a short poem describing how HTTP sends data between computers.  

*When you type a website's name and hit "go,"
Your computer sends a request to and fro.
The website's computer then responds with care,
Sending back pieces for your screen to share.
Like a package split into slices small,
Your screen assembles them, one and all.
HTTP, the messenger, makes it clear,
Connecting computers, far and near.*

2. Describe how HTML, CSS, and JS files are “parsed” in the browser.  

Imagine you have a recipe for making a cake. HTML is like the main ingredients list, telling you what you need. CSS is like the decorations and colors you use to make the cake look pretty. JavaScript is like the special instructions that tell you what to do with the ingredients and decorations.

When you open a webpage, your browser reads the HTML first, just like reading the ingredients list. It figures out what needs to go where on the page. Then, it looks at the CSS to see how to style everything, like deciding what color the text should be or how big pictures should be.

After that, it's time for JavaScript. The browser reads through the JavaScript instructions, which might say things like "make this button change color when clicked" or "show a pop-up message after five seconds."

So, HTML, CSS, and JavaScript are like different parts of a recipe that the browser follows step by step to create and display a webpage. It's like making a cake: first, you gather your ingredients (HTML), then you decorate it (CSS), and finally, you add special touches (JavaScript) to make it just right.  

3. How can you find images to add to a Website?  

There are many ways to find images to add to your website. options include search engines, stopk photo websites, graphic design tools, social media, or even creating your own.  

4. How do you create a String vs a Number in JavaScript?  

String: This is a sequence of text known as a string. To signify that the value is a string, enclose it in single or double quote marks.  
  
    let myVariable = 'Bob'; or let myVariable = "Bob";  

 Number: This is a number. Numbers don't have quotes around them.

    let myVariable = 10;

5. What is a Variable and why are they important in JavaScript?  

Variables are containers that store values. You start by declaring a variable with the let keyword, followed by the name you give to the variable:

6. What is an HTML attribute?  
 
An HTML attribute is additional information or properties that you can add to HTML elements to provide more details about them or to specify how they should behave. Attributes are added directly within the opening tag of an HTML element and consist of a name and a value, separated by an equals sign (=).

For example, in the HTML code \<img src="example.jpg" alt="Example Image">, **src** and **alt** are attributes.  

7. Describe the Anatomy of an HTMl element.  

Example: \<a href="https://example.com">Click here to visit Example\</a>  

Opening Tag: \<a href="https://example.com">  
Attribute: href="https://example.com"  
Content: Click here to visit Example  
Closing Tag: \</a>  

8. What is the Difference between \<article> and \<section> element tags?  
  
Both the \<article> and \<section> elements are used to divide content into meaningful sections in HTML, but they have different purposes and semantic meanings:
  
Article: This element represents a self-contained piece of content that could be distributed and reused independently. It typically contains content that makes sense on its own and can be syndicated, like a blog post, news article, forum post, or a comment.  

Section: This element is used to group related content together within a document. It doesn't imply any particular meaning about the content it contains and is more generic in nature.

9. What Elements does a “typical” website include?  
    • Header
    • Body  
    • Nav  
    ¶ Headings  
    • Links, Images, Forms, Tables  
    • Sections/Article  
    • Footer  

10. How does metadata influence Search Engine Optimization?  
  
  Metadata in SEO, like title tags and meta descriptions, provides search engines with concise information about a webpage's content. Optimizing metadata with relevant keywords can improve a page's visibility and click-through rates in search results. Additionally, structured data markup such as schema.org can enhance search engine understanding of page content, leading to richer search results.  
    

11. How is the \<meta> HTML tag used when specifying metadata?  
  
The \<meta> HTML tag is used to specify metadata within the \<head> section of an HTML document. It doesn't have a closing tag and is self-closing. Metadata specified with the \<meta> tag includes information like the character encoding of the document (charset attribute), viewport settings for responsive design (viewport attribute), and directives for search engines such as robots (robots attribute). Additionally, the \<meta> tag is commonly used to define the title (title attribute) and description (description attribute) of a webpage for search engine optimization (SEO) purposes.