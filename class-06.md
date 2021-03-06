# Explore the Tech!

in today's blog, I am goint to discuss several topics related to **web development** and **Javascript**. So, _let's get started!_

### 1. Learning the problem domain:
The author of this [article](https://simpleprogrammer.com/understanding-the-problem-domain-is-the-hardest-part-of-programming) says that from his point of view, the hardest part about programming is understanding the problem domain. He says that sometimes it is so complicated that it feels like a double-sided puzzle. However, to understand it, we can do one of the following:
* **Make the problem domain easier**: by cutting out cases and narrowing your focus to a particular part of the problem.
* **Get better at understanding the problem domain**: make sure you understand a problem inside and out before you try and solve it with code.  It is much more expensive and time consuming to do things over than it is to do them right the first time. 

### 2. Object Literals in _Javascript_:
Objects group together a set of variables and functions to create a model of a something you would recognize from the real world. In an object, variables and functions take on new names, where variables become **properties**, and functions become **methods**. Th emost popular way to create objects is the ***literal notation***
- Example:
`var toystore{`

  `name = "happy time";`
  
  `location: "Amman";`
  
  `numToys: 50;`
  
  `reserved: 32;`
  
  `availableToys: function (){`
  
    `return this.numToys - this.reserved;}`
    
 To access an obkect, we can use the ***dot notation*** or ***square brackets***. `var storeName = toySotre.name;` or `var storeName = toySotre['name'];`, `freeToys = availableToys();`


### 3. Document Object Model in _Javascript_:
The Document Object Model (DOM) specifies how browsers should create a model of an HTML page and how JavaScript can access and update the contents of a web page while it is in the browser window. The following are the main functionalities of _DOM_:
* When the browser loads a web page, it creates a model of the page in memory.
* Defines methods and properties to access and update each object in this models which in turn updates what the user sees in the browser.
* The DOM states what your script can "ask the browser about the current page, and how to tell the browser to update what is being shown to the user.

Also, Each node is an object with _methods_ and _properties_. Scripts access and update this **DOM tree** (not the source HTML file), where any changes made to the DOM tree are reflected in the browser. Accessing and updating the DOM tree involves two steps:
##### 1. Locate the node that represents the element you want to work with.
##### 2. Use its text content, child elements, and attributes.
To access elements in DOM tree, the _DOM Queries_ are used. DOM queries may return one element, or they may return a Nodelist, which is a collection of nodes. The following are examples of methods that return a single/multiple element node/nodelist:
* `getElementByld('id')`. Single
* `querySelector('css selector')`. Single
* `getElementsByClassName('class')`. Multiple
* `getElementsByTagName('tagName')`. Multiple
* `querySelectorAll('css selector')`. Multiple

Also, to select an element from a nodelist, two ways are used:
##### 1. The `item` method. `var fItem = element.item(0);`
##### 2. Array Syntax. `var fItem = elements[0];`

To acces a _nodelist_, we can loop through it using _for_ loop. Also, to add and remove the HTML content, from a DOM tree, we can use the following:
* `innerHTML` property: updating the entire fragment. You can access and amend the contents of an element, including any child elements.
* DOM manipulation: updates individual nodes in the tree. Also, DOM manipulation offers another technique to add new content to a page using `createElement()`, `createTextNode()` and `appendChild()`. Furthermore, DOM manipulation is used to remove elements by:
##### 1. storing the element to be removed in a variable.
##### 2. store the parent of that element in a variable.
##### 3. remove the element from its containing element.

In conclusion, DOM trees have four types of nodes: _document nodes, element nodes, attribute nodes, and text nodes._ You can select element nodes by their _id_ or _class attributes_, by _tag name_, or using _CSS selector_ syntax. Whenever a DOM query can return more than one node, it will always return a **Nodelist**.
From an element node, you can access and update its content using properties such as _textContent_ and _innerHTM_L or using _DOM manipulation_ techniques.
An element node can contain multiple text nodes and child elements that are siblings of each other. In older browsers, implementation of the DOM is inconsistent. However, Browsers offer tools for _viewing_ the DOM tree .

