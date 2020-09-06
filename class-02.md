# Explore the Tech!

In today's blog, I am goint to discuss some topics related to web development in **HTML, CSS, and Javascript**. So, _let's get started!_

### 1. Text in _HTML_:
Text in HTML is represted in various tags, which are desrcibed as follows:
* Headingds `<h1>` to `<h6>`: contains _six_ levels of headings, where `<h1>` indicates the most important heading, and `<h6>` indicates the least important headings.
* Paragraphs `<p>`: container of paragprahs of text, where each paragraph is shown on a new linewith some space between it and any subsequent paragraphs.
* Bold `<b>` and Italic `<i>`.
* Supscripts `<sup>` such as the suffixes of dates or mathematical concepts, and Subscripts `<sub>` used commonly with foot notes or chemical formulas.
* Line breaks `<br />` and Horizental Rules `<hr />`.
* Strong `<strong>` that indicates important content an shown as blod. While Emphasis `<em>` is shown as italic and indicates emphasis that subtly changes the meaning of a sentence.
* Quotations: `<blockquote>` that is used for longer quotes that take up an entire paragraph. And `<q>` that is used for shorter quotes that sit within a paragraph. 
* Abbreviations `<abbr>` and Acrynoms `<acrynom>`.
* Citations `<cite>` and definitions `<dfn>`.
* Author Details: `<address>`.
* Changes to content: `<ins>` used to show content that has been inserted into a document, `<del>` to show text that has been deleted from it, and `<s>` that indicates something that is no longer accurate or relevant (but that should not be deleted).


### 2. Introducting _CSS_:
So, what the CSS does is that it allows the developer to create rules that specify how the content of an element should appear. This will make web pages more attractive and appealing to the eye.
CSS works by associating rules with HTML elements. These rules tells the browser how the content of specified elements should be displayed on the screen. A _CSS rule_
contains 2 parts: a selector and a declaration. For example, in this CSS command, `p {font-family: Arial;}`, `p` is the **selector** and `font-family` is the **declaration**. 
Also, declarations contains 2 parts: property and value. `font-family` is the **property** and `Arial` is the **value**.
However, if there are 2 or more rules that apply to the same element, the rule is chosen based on the following:
* Last rule.
* Specifity.
* Improtant. `!important`

There are 2 ways to associate the **CSS** with the HTML file: _internal_ using `<style>` tag, and external using `<link>` tag to a separate `.css` file.


### 3. Basic _Javascript_ instructions:
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


### 4. _Decisions_ and _Loops_:
##### 1. Decisions:
Comparison operators are used to compare 2 values to see if they are equal to each other or not. Comparison operators return a single value of `true` or `false`. The following is a list of the comparison operators used in _Javascript_:
* `==`: is equal to (compares the value, not the data type).
* `!=`: not equal to.
* `===`: strict equal to (compares the value and the datatype).
* `!==`: strict not equal to.
* `>`: greater than.
* `<`: less than.
* `=>`: greater than or equal to.
* `<=`: less than or equal to.

Also, _Javascript_ uses a list of logical operators to compare the results of more than one comparison operator. Examples of logical operators are the following:
* `&&`: and (returns true if both are true).
* `||`: or (returns true if one is true).
* `!`: not (returns true if the result is false).

##### 2. Loops:
  1. `for`: tells the code to execute for a cpecified number of times according to some condition in the _counter_. The condition is made up of 3 parts as follows:
  
   + initialization: `var i = 0;`.
   + condition: `i < 10;`.
   + update: `i++;`.
  In the previouse example, the first time the code runs, `i` is assigned to `0`. Then, each time the code runs, the condition `i < 10;` is checked. If `true`, the code inside the loop is run and the value of `i` is increased by `1` in the _update step_.
  
  2. `while`: the difference between `for` and `while` is the structure of the loop. In `while`, it is like telling to code to keep running until the condition is no longer `true`.
  
   + condition: `i < 10;` (written before the body of the loop).
   + update: `i++;` (written after the body of the loop).


