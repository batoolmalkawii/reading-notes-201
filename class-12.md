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
***Introduction:***

 The `<canvas>` element has only two attributes, `width` and `height`. These are both optional and can also be set using `DOM` properties. When no width and height attributes are specified, the canvas will initially be `300px` wide and `150px` high. 
 
 The `<canvas>` element differs from an `<img>` tag in that, like for `<video>`, `<audio>`, it is easy to define some _fallback content_, to be displayed in older browsers not supporting it. Browsers that don't support `<canvas>` will _ignore_ the _container_ and render the fallback content inside it. Browsers that do support `<canvas>` will _ignore_ the _content_ inside the container, and just render the canvas normally.
 
`<canvas>` element requires the closing tag (`</canvas>`). If this tag is not present, the rest of the document would be considered the fallback content and wouldn't be displayed.
The `<canvas>` element creates a _fixed-size_ **drawing surface** that exposes one or more rendering contexts, which are used to create and manipulate the content shown.

***Drawing Shapes:***

`<canvas>` only supports two primitive shapes: `rectangles` and `paths` (lists of points connected by lines). All other shapes must be created by combining one or more paths. The following are functions for drawing `rectangles`:
* `fillRect(x, y, width, height)`: Draws a filled rectangle.
* `strokeRect(x, y, width, height)`: Draws a rectangular outline.
* `clearRect(x, y, width, height)`:Clears the specified rectangular area, making it fully transparent.

The following are the steps for drawing `paths`:
* `beginPath()`: Creates a new path. Once created, future drawing commands are directed into the path and used to build the path up.
* `Path methods`: Methods to set different paths for objects.
* `closePath()`: Adds a straight line to the path, going to the start of the current sub-path.
* `stroke()`: Draws the shape by stroking its outline.
* `fill()`: Draws a solid shape by filling the path's content area.

Other drawing method:
* `lineTo()`: straight lines.
* `moveTo()`: changing the starting point.
* `arc()` & `arcTo()`: arcs and circles.
* `quadraticCurve()`: quadratic curves.

***Coloring Shapes:***

If we want to apply colors to a shape, there are two important properties we can use: `fillStyle` and `strokeStyle`.
There are several properties which allow us to style lines:
* `lineWidth = value`: Sets the width of lines drawn in the future.
* `lineCap = type`: Sets the appearance of the ends of lines.
* `lineJoin = type`: Sets the appearance of the "corners" where lines meet.
* `miterLimit = value`: Establishes a limit on the miter when two lines join at a sharp angle, to let you control how thick the junction becomes.
* `getLineDash()`: Returns the current line dash pattern array containing an even number of non-negative numbers.
* `setLineDash(segments)`: Sets the current line dash pattern.
* `lineDashOffset = value`: Specifies where to start a dash array on a line.

***Drawing Text***
The canvas rendering context provides two methods to render text:
* `fillText(text, x, y [, maxWidth])`: Fills a given text at the given (x,y) position. Optionally with a maximum width to draw.
* `strokeText(text, x, y [, maxWidth])`: Strokes a given text at the given (x,y) position. Optionally with a maximum width to draw.
