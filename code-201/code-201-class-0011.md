# **Reading Notes | 4 MARCH 2024**

# Class 011  

### *Bookmarks:*  

[Images in HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Images_in_HTML)  
[From object to iframe — other embedding technologies](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Other_embedding_technologies)

## **Questions & Answers**  

### Explain how the ability to use video and audio on the web has evolved since the early 2000s

Video and audio on the web have evolved from basic plugins like Flash to native support in browsers through HTML5. This evolution has led to better compatibility, accessibility, and performance.  
  
### Describe the use of the src and controls attributes in the \<video> element

The `src` attribute in the `<video>` element specifies the URL of the video file, while the `controls` attribute adds playback controls like play, pause, and volume to the video player.

### Why is it important to have fallback content inside the \<video> element?

Fallback content inside the `<video>` element ensures that users with browsers that don't support the `<video>` element or the video format can still access alternative content, such as a text description or a link to download the video.

### Write a very short story where <audio> and <video> are characters

Once upon a time, <audio> and <video> were inseparable friends. They roamed the digital landscape, sharing stories and melodies with anyone who cared to listen or watch.

### How does Grid layout differ from Flex?

Grid layout is a two-dimensional layout system, allowing for precise control over both rows and columns, while Flexbox is primarily a one-dimensional layout system, ideal for arranging items in a single direction—either horizontally or vertically.

### Grid container, grid item, and grid line are a few important terms to understand when using Grid. Please describe these terms in a few sentences

In Grid layout, the grid container is the parent element that contains grid items arranged in rows and columns. Grid items are the child elements inside the grid container, and grid lines are the lines that form the boundaries of the grid cells.

The grid container is the parent element that contains grid items arranged in rows and columns. Grid items are the child elements inside the grid container, and grid lines are the lines that form the boundaries of the grid cells.

### Besides making a site visually appealing across different screen sizes, why should developers make images responsive?

Responsive images ensure faster loading times and better user experience across different devices by delivering appropriately sized images based on the device's screen resolution and size.

### Define the following \<img> attributes srcset and sizes. Write an example of how they are used

The srcset attribute in the <img> element allows specifying multiple image sources with different resolutions or sizes, while the sizes attribute defines the viewport sizes for which each image source is applicable.

    For example: <img src="image.jpg" srcset="image-2x.jpg 2x, image-3x.jpg 3x" sizes="(max-width: 600px) 100vw, (max-width: 1200px) 50vw, 25vw">

### How is srcset more helpful for responsive images than CSS or JavaScript??

srcset is more helpful for responsive images than CSS or JavaScript because it allows browsers to choose the most appropriate image source based on device capabilities and viewport size without additional scripting or styling, improving performance a
