# Explore the Tech!
In today's blog, I am going to discuss some topics related to _Web Development_. Specifically, **HTML, CSS, AND JavaScript**. So, _Let's get started!_


### 1. Lists in _HTML_:
There are several types of lists in HTML, described as follows:
* Ordered Lists: creates a **Numbered** list. It is created using `<ol>` element, and each item is inserted between `<li>` tags.
* Unordered Lists: creates a **Bullet** list. It is created using `<ul>` element, and each item is inserted between `<li>` tags.
* Definition Lists: creates a list containing a series of **terms** and their **definitions**. It is created using `<dl>` element, and each term is inserted between `<dt>` tags while `<dd>` is for definitions. 


### 2. Boxes:
Each tag in HTML is considered a _Box_. The specifications, styles, and sizes of these boxes can be controlled by a number of _CSS_ properties, described as follows:
* Box Dimensions: `width` and `Height`.
* Limiting Width: `min-width` and `max-width`.
* Limiting Height: `min-height` and `max-height`.
* Overflow Content: `overflow` with the following options: `scroll` and `hidden`.
* Borders: `border`, `border-width`, `border-image`, `border-radius` and `border-style`
* Padding: `padding`, `padding-top`, `padding-bottom`, `padding-left` and `padding-right`.
* Margin: `margin`, `margin-top`, `margin-bottom`, `margin-left` and `margin-right`.
* Display: `display` allows you to turn an inline element into a block-level element or vice versa, and can also be used to hide an element from the page. The options for this property are: `inline`, `block`, `inline-block` and `none`.
* Hiding Boxes: `visibility`, the options are: `visible` and `hidden`.
* Box Shadow: `box-shadow` allows you to add a drop shadow around a box. 


### 3. Arrays in _Javascript_:
An array is a special type of variable thats tores a list of values. using an array is considered a better solution If you don't know how many items a list will contain, rather
than creating enough variables for a long list. Also, arrays can be accessed and modified in multiple ways.
An array can be created using the following steps:
1. `var`.
2. ArrayName `colors`.
3. `new Array`
4. Values `('white','black','custom');`

### 4. Decisions and Loops in _Javascript_:
1. Switch Statament:
A switch statement starts with a variable called the switch value. Each case indicates a possible value for this variable and the code that should run if the variable matches that value. The usefulness of _switch_ over the _if statement_ is when you have a default option that is run if none of the cases match, if a match is found, that code is run; then the break statement stops the rest of the switch statement running (providing better performance than multiple if statements).
    - Example of Switch statement:
`switch (level) {
case 'O ne ':
title= 'Level 1 ' ;
break;
case 'Two':
tit 1 e = ' Level 2 ' ;
break;
case ' Three' :
title = 'Level 3' ;
break ;
default :
title= 'Test';
break;
}`

2. Loops:

`for`: tells the code to execute for a cpecified number of times according to some condition in the _counter_. The condition is made up of 3 parts as follows:
  
   + initialization: `var i = 0;`.
   + condition: `i < 10;`.
   + update: `i++;`.
  In the previouse example, the first time the code runs, `i` is assigned to `0`. Then, each time the code runs, the condition `i < 10;` is checked. If `true`, the code inside the loop is run and the value of `i` is increased by `1` in the _update step_.
  
`while`: the difference between `for` and `while` is the structure of the loop. In `while`, it is like telling to code to keep running until the condition is no longer `true`.
  
   + condition: `i < 10;` (written before the body of the loop).
   + update: `i++;` (written after the body of the loop).
   
`do-while`: The main difference between a while loop and a do whi 1 eloop is that the statements in the code block come before the condition. This means that those statements are run once whether or not the condition is met.
      - Example:
  `do {
    msg += i + ' x 5 = ' + (i * 5) + '<br I>' ;s
    i++;
    } while (i<1);
    console.log('Hi!');
    `
