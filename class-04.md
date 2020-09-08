# Explore the Tech!

In today's blog, I am going to discuss some topics related to web development in **HTML, CSS and Javascript**. So, _let's get started!_

### 1. Links in _HTML_:
Links are created using the `<a>` element which has an attribute called `href`. The value of the `href` attribute is the page that you want people to go to when they click on the link `<a href="about.html">About Film Folk</a>`. Links can lead to the following:
* Other sites.
* Other pages in the same site, where URLS can be _absolute_ or _relative_.
* Specific part of the same page.
* Specific part of another page
* Email Links `mailto`.

Also, links can be opened in new windows using the `target` attribute.

### 2. Layouts in _CSS_:
**a.** CSS treats each HTML element as if it is in its own box. This box will either be a block-level box or an inline box:
* Block-level: start on a new line. `<h1> <p> <ul> <li>`
* Inline-level: flow in between surrounding text. `<img> <b> <i>`

**b.** Using th `position` property, CSS has the following positioning schemes that allow you to control the layout of a page: 
* normal flow. `position:static`
* relative positioning. `position:relative`
* absolute positioning. `position:absolute`
* fixed positioning. `position:fixed`

**c.** Also, the `float` property allows you to take an element in normal flow and place it as far to the left or right of the containing element as possible. This can be `float:right` or `float-left`. Furthermore, float can be cleared using the `clear` property, the values can be `left`, `right`, `both` and `none`. To create multi-column layouts with floats, The following three CSS properties are used to position the columns next to each other:
* `width`: sets the width of the columns.
* `float`: positions the columns next to each other.
* `margin`: creates a gap between the columns.

**d.** Because screen sizes and display resolutions vary so much, web pages might not be displayed as desired by the designer. However, designers follow two methods in terms of layout design, described as follows:
* Fixed-width layout: do not change size as the user increases or decreases the size of their browser window. `px`
* Liquid layout: stretch and contract as the user increases or decreases the size of their browser window. `%`


### 3. Functions, Methods, and Objects in _Javascript_:
Functions let you group a series of statements together to perform a specific task. If different parts of a script repeat the same task, you can reuse the function (rather than repeating the same set of st atements). 
* _To declare a function,_ the following structure is defined: `function`: keyword, `area (width, height)`: function name (parameters),  `{ //some statements };`: function body.  
* _To call a function_: functionName(real parameters). `area (width, height)`.
* _To get a value out of a function_: `return(value)`.


### 4. Pair Programming:
Pair programing is a technique used to foster a collaborative environment while developing key industry skills, and it is used commonly in many agile work environments.
pair programming involves two roles: 
* Driver: the programmer who is typing and the only one whose hands are on the keyboard. Manages the text editor, switching files, version control, awriting—code.
* Navigator: uses their words to guide the Driver but does not provide any direct input to the computer. 
Using pai programming touches on all four skills (speaking, listening, reading and writing): _developers explain out loud what the code should do, listen to others’ guidance, read code that others have written, and write code themselves._

The following are reasons _why_ you should do _pair programming_:
1. Greater efficiency.
2. Engaged collaboration
3. Learning from fellow students.
4. Social skills.
5. Job interview readiness.
6. Work environment readiness.




