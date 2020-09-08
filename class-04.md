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
A. CSS treats each HTML element as if it is in its own box. This box will either be a block-level box or an inline box:
* Block-level: start on a new line. `<h1> <p> <ul> <li>`
* Inline-level: flow in between surrounding text. `<img> <b> <i>`

B. Using th `position` property, CSS has the following positioning schemes that allow you to control the layout of a page: 
* normal flow. `position:static`
* relative positioning. `position:relative`
* absolute positioning. `position:absolute`
* fixed positioning. `position:fixed`

C. Also, the `float` property allows you to take an element in normal flow and place it as far to the left or right of the containing element as possible. This can be `float:right` or `float-left`. Furthermore, float can be cleared using the `clear` property, the values can be `left`, `right`, `both` and `none`. To create multi-column layouts with floats, The following three CSS properties are used to position the columns next to each other:
* `width`: sets the width of the columns.
* `float`: positions the columns next to each other.
* `margin`: creates a gap between the columns.

D. Because screen sizes and display resolutions vary so much, web pages might not be displayed as desired by the designer. However, designers follow two methods in terms of layout design, described as follows:
* Fixed-width layout: do not change size as the user increases or decreases the size of their browser window. `px`
* Liquid layout: stretch and contract as the user increases or decreases the size of their browser window. `%`
