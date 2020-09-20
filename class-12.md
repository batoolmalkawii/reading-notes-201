# Explore the Tech!

In today's blog, I am going to discuss some interesting topics related to web development in ***HTML*** and ***JavaScript***, specifically **ChartJS**. So, _let's get started!_


### 1. Creating animated charts with _Chart.JS_:
Charts are far better for displaying data visually than tables and have the added benefit that no one is ever going to press-gang them into use as a layout tool. They’re easier to look at and convey data quickly, but they’re not always easy to create. Chart.js, a JavaScript plugin that uses HTML5’s canvas element to draw the graph onto the page. 
In chart.JS, you can download ***Chart.JS*** and create several types of chart, such as:
* Line charts.
* Pie charts.
* Bar charts.
The great things about Chart.js are that it’s simple to use and really very flexible.


### 2. Canvas in _HTML_:
 The `<canvas>` element has only two attributes, `width` and `height`. These are both optional and can also be set using `DOM` properties. When no width and height attributes are specified, the canvas will initially be `300px` wide and `150px` high. 
 The `<canvas>` element differs from an `<img>` tag in that, like for `<video>`, `<audio>`, it is easy to define some _fallback content_, to be displayed in older browsers not supporting it. Browsers that don't support `<canvas>` will _ignore_ the _container_ and render the fallback content inside it. Browsers that do support `<canvas>` will _ignore_ the _content_ inside the container, and just render the canvas normally.
`<canvas>` element requires the closing tag (`</canvas>`). If this tag is not present, the rest of the document would be considered the fallback content and wouldn't be displayed.
The `<canvas>` element creates a _fixed-size_ **drawing surface** that exposes one or more rendering contexts, which are used to create and manipulate the content shown.
