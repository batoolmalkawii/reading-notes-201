# Explore the tech! 
In today's blog, I am going to talk about some topics in **HTML**. _So, let's get started!_


### 1. Structure in HTML:
**HTML** is maily used to structure the web page, it uses elments to describe the structure of pages.
To do this, HTML used ***tags*** as building blocks. These tags might contain features named _attributes_. They are used to provide additional information about the contents of an element.
There are several parts of the _HTML_ page:
* `<head>`.
* `<body>`.
* `<footer>`.
* `<title>`.


### 2. Extra Markup in HTML:
The following is features you can use in HTML5:
* DOCTYPES: tell browsers which version of HTML you are using.
* COMMENTS. `<!-- -->`
* ID attribute.
* CLASS attribute.
* Inline elements.
* Block elements.
* Grouping Text and Elements In a Block.
* Frames.
* <meta> tag allows you to supply all kinds of information about your web page.
* Escape characters are used to include special characters in your pages such as <, >, and ©.
* <div> and <span> elements allow you to group block-level and inline elements together.


### 3. HTML5 Layout:
Alongside with `<div>` tag used to divide parts of the webpage, _HTML5_ have introduced new elements for the layout. The following are examples of these elements:
* `<header>` and `<footer>`: appears at the top and bottom of every page on the site.
* `<nav>`: used to contain the major navigational blocks on the site.
* `<article>`: acts as a container for any section of a page that could stand alone and potentially be syndicated.


### 4. Process and Design in HTML:
There are several ***Important*** questions to consider when designing a website, some are described as follows:
* Who will visit my website?
* Why will they visit my website?
* What information they are looking for?
* How often will they visit my website?

After answering these question, a developer starts to organize the information into sections or pages. This is done by the following methods: 
* ##### Site Maps: a diagram of the pages used to structure the site. It shows how those pages can be grouped.
* ##### Wireframes: a simple hierarchy sketch of the key information that needs to go on each page of a site. 

In particualr, ***communication*** is the primary goal of visual design. Communication can be successfully accomplished by _prioritizing, organizing, and carefully choosing the content of the page._
For instance, the developer should consider the features of _visual hierarchy, grouping and similarity,_ including details like (_size, color, style, images etc.._).



Now, I'm going to talk about ***JAVASCRIPT***, an intersteng programming language used in web development. _So, let's get started!_

### 5. How HTML, CSS, and Javascript fit together?
* HTML: content layer `.html`.
* CSS: presentation layer `.css`.
* Javascript: behaviour later `.js`. Can also be written inside the html file with the tag `<script>'.
These 3 layers form what is called **Progressive Enhancement**.

### 6. Basic Javascript instructions:
Here, I'm going to summarize some basic concepts and instructions related to _Javascript_.
* **Script:** a series of instructions followed by a computer to accomplish a task.
* **Statement:** a single instruction used in the script. A group of statements form a script.
* **Comments:** explaines what the code does, ignored when executing. `\\`, `\*`.
* **Variables:** containers of information defined by a unique name. `var x = 3`.
* **Datatypes:** can be `string`, `boolean`, `int`, `numeric`,etc..

The following are some basic rules to name a variable in JS:
1. must begin with a letter, `$`, `_`, not with a number.
2. can contain letters, `$`, `_`, and numbers.
3. cannot use keywords or reserved words.
4. names are case-sensitive.
5. should describe the info it contains.
6. does not contain spaces.



### 7. What is a _Script_, and how to write one?
A script is a series of instructions that a computer can follow step-by-step to achieve a goal, Just like recipes, handbooks and manuals. Then, a browser can use different parts of the script depending on how the user interacts with the webpage.

To write a script, the developer need to first state goal and then list the tasks that need to be completed to achieve it. In other words, the developer must Start with the big picture of what he wants to achieve, and break
that down into smaller steps, as the following:
  1. Define the goal.
  2. Design the script: using **flowcharts or steps**.
  3. Code each step: each step for every task shown in a flowchart needs to be _written_ in a language the computer can understand and follow.
  
  In conclusion, for someone who wants to learn a programming language, he must start learning how to think like a computer. Then, get fimiliar with the **vocabulary** and **syntax** of the language.
  
  
### 8. Expressions in Javascript:
  An _expression_ results in a single value. Generally, there are two types of expressions:
    1. Expressions that just assign to a value or a variable. `var color = 'beige';`
    2. Expressions that use multiple values to return a single value. `var area = 3 * 2;`
 Basically, expressions rely on _operators_ which allow developers to create a single value from one or more values. The following are the types of used operators:
  * Arithmetic operators. `area = 3 * 2;`
  * Logical operators. `buy= (5 > 3) && (2 < 4);`
  * Assignment operators. `color = 'beige';`
  * String operators. `greeting= 'Hi 1 + 'Mol ly';`
  * Comparison operators. `buy = 3 > 5;`
  
  
### 9. What is a _Function_?
  Functions let the developer group a sequence of statements together to perform a specific task. If different parts of a script repeat the same task, the function can be
reused. To declare a function, it must be given a name, writing the statements that make up the task required from the function in curly brace `{ }`. 
**Example:**
`function updateMessage() {
var el = document.getElementByld('message'};
el .textContent = msg;
}`
  + `function updateMessage()`: fuction keyword and name 
  + `{var el = document.getElementByld('message'}; el .textContent = msg;}`: code block (function body).
To call a function, the name of the function is written like this: `updateMessage();`. But if the function returns a value or contains parameters, they must be included in the call. For example, if the function returns a value, the function must be assigned to a `var` first: `var result=updateMessage();;`, so that the output can be stored in that variablr. Also, if the function contains parameters, it would look like this: updateMessage(height, width);;
