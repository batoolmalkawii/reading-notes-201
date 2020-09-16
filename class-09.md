
# Explore the Tech!

In today's blog, I am going to be discussing several topics related to web development in ***HTML, CSS, and Javascript***. So, _let's get started!_

### 1. Forms in _HTML_:
Forms are defined like this: `<form action="", method="">`, and there are several types of form controls that you can use to collect information from visitors to your site, such as follows:
* Adding text: `<input type="text">`, `<input type="password">`, `<textarea>` 
* Making Choices: `<input type="radio">`, `<input type="checkbox">`, `<select><option>`.
* Submitting forms: `<input type="submit">`.
* Uploading files: `<input type="file">`.
* Date: `<input type="date">`.
* Labeling of elements: `<label>`.
* Groubing form elements: `<fieldset><legend>`.
* E-mail: `<input type="email">`.
Search: `<input type="search">`.

Also, form work as follows:
1. A user fills in a form and then presses a button to submit the information to the server.
2. The name of each form control is sent to the server along with the value the user enters or selects.
3. The server processes the information using a programming language such as PHP, C#, VB.net, or Java. It may also store the information in a database.
4. The server creates a new page to send back to the browser based on the information received.


### 2. Lists, tables, and forms in _CSS_:
There are several CSS properties that were created to work with specific types of HTML elements, such as lists, tables, and forms, and some are discussed in the following:
* `list-style-type`: allows you to control the shape or style of a bullet point (also known as a **marker**).
* `list-style-image`: pecifies an image to act as a bullet point.
* `list-style-position`: indicates whether the marker should appear on the inside or the outside of the box containing the main points.
* `list-style`: allows you to express the markers' style, image and position properties in any order.
**Table properties**: 
* `width`: to set the width of the table.
* `padding`: to set the space between the border of each table cell and its content.
* `text-transform`: to convert the content of the table headers to uppercase.
* `letter-spacing`, `font-size`: to add additional styling to the content of the table headers.
* `border-top`, `border-bottom`: to set borders above and below the table headers
* `text-align`: to align the writing to the left of some table cells and to the right of the others.
* `background-color`: to change the background color of the alternating table rows.
* `:hover`: to highlight a table row when a user's mouse goes over it.
* `empty-cells`: to specify whether or not their borders should be shown.
* `border-spacing`: allows you to control the distance between adjacent cells.
**Forms Properties**:
* Text Input: `font-size`, `color`, `background-color`, `border`, `border-radius`, `background-image`.
* Submit Buttons: `color`, `text-shadow`, `border-bottom`, `background-color`.
* Fieldsets and Legends: `width`, `color`, `background-color`, `border`, `border-radius`, `padding`.
**Cursor**: `auto`, `crosshair`, `default`, `pointer`, `move`, `text`, `wait`, `help`, `url("cursor.gif");`


### 3. Events in _Javascript_:
When the user interacts with the HTML on a web page, there are 3 steps involved in getting it to trigger some JavaScript code. These steps are known as ***event handling***:
1. Select the **element** node(s) you want the script to respond to.
2. Indicate which **event** on the selected node(s) will trigger the response.
3. State the **code** you want to run when the event occurs.

**Event handlers** let you indicate which event you are waiting for on any particular element. There are three types of event handlers: 
* HTML event handlers: _bad practice_.
* Traditional DOM event handlers: _better than HTML handlers_.
* DOM level2 event listeners: _the favored way_.

When an event occurs, the event object tells you information about the event, and the element it happened upon. Creating event listeners for a lot of elements can slow down a page, but event flow allows you to listen for an event on a parent element. Also, the event object has methods that change: the default behavior of an element and how the element's ancestors respond to the event.

When calling a function, the event object's target property is the best way to determine which element the event occurred on. But you may see the approach below used; it relies on the `this` keyword.

**Events Types**:
* W3C DOM EVENTS.
* HTML5 EVENTS.
* BOM EVENTS.
