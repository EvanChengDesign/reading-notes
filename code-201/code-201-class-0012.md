# **Reading Notes | 05 MAR 2024**

# Class 012  

### *Bookmarks:*  

[Drawing Shapes with Canvas](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Drawing_shapes)  
[Applying Styles and Colors - Canvas API](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Applying_styles_and_colors)  
[Drawing Text - Canvas API](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Drawing_text)

## **Questions & Answers**  

### What does the \<canvas> allow a developer to achieve?

The \<canvas> element in HTML allows developers to dynamically generate graphics, animations, and interactive content using JavaScript. It provides a drawing space within the web page where developers can programmatically create and manipulate graphics, such as lines, shapes, text, images, and animations.

### What is the importance of the closing \</canvas> tag?  

The closing \</canvas> tag is important because it marks the end of the canvas element. Like all HTML elements, it's essential to properly close the \<canvas> tag to adhere to the HTML syntax rules. Failure to close the tag correctly can lead to rendering issues or unexpected behavior in the web page.

### Explain what the getContext() method does

obtain the rendering context and provides methods and properties for drawing on the canvas. The getContext() method accepts a parameter specifying the type of context desired, such as "2d" for a 2D rendering context or "webgl" for a WebGL rendering context.

For example, to get a 2D rendering context, you would use:

    var canvas = document.getElementById('myCanvas');
    var context = canvas.getContext('2d');  

Once you have obtained the context, you can use various drawing methods and properties provided by the context object to draw shapes, text, images, and manipulate pixels on the canvas.

### What is Chart.js and how it can be brought into your project?  

Chart.js is a popular JavaScript library for creating responsive and interactive charts and graphs in web applications. It provides an easy-to-use API for developers to create various types of charts, including line charts, bar charts, pie charts, and more.  

To bring Chart.js into your project, you can include it via a CDN (Content Delivery Network) or download and include the library in your project files. Then, you simply need to link the Chart.js script in your HTML file.

### List 3 different Chart types you can create using Chart.js  

Three different chart types you can create using Chart.js are:

* Line charts
* Bar charts
* Pie charts

### What are some advantages to displaying data via a chart over a table?  

Displaying data via a chart offers several advantages over a table, including:

* Enhanced visual representation: Charts provide a visual representation of data, making it easier for users to grasp patterns and trends at a glance.  

* Simplified understanding: Charts simplify complex data sets, making it easier for users to understand and interpret the information.  

* Interactive exploration: Charts often offer interactive features such as tooltips and zooming, allowing users to explore data in more detail.

### How could Chart.js aid your previously created applications visually?

Chart.js could aid your previously created applications visually by allowing you to present data in a more engaging and intuitive way. By incorporating Chart.js charts into your applications, you can enhance the user experience and make data analysis more accessible to your audience.
