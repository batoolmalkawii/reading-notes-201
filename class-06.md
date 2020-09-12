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


