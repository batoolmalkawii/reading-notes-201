# Explore the Tech!

In today'sblog, I am going to discuss some topics related to ***Object-Oriented Programming***. So, _let's get started!_

### 1. Domain Modeling:
An _object-oriented model_ is an entity that stores data in _properties_ and encapsulates behaviors in _methods_. To define the same properties between many objects, a constructor function is used. In general, object-oriented programming in JavaScript looks like the following:

* The `new` keyword instantiates (i.e. creates) an object.
* The constructor function initializes properties inside that object using the `this` variable.
* The object is stored in a `variable` for later use.

Example:
```
var EpicFailVideo = function(epicRating, hasAnimals) {
  this.epicRating = epicRating;
  this.hasAnimals = hasAnimals;
}
var parkourFail = new EpicFailVideo(7, false);
var corgiFail = new EpicFailVideo(4, true);
```

Also, _random number generators_ are useful when using objects and contructors.


### 2. Tables in _HTML_:
A table represents information in a grid format. Each block in the grid is referred to as a _table cell_. In HTML, atable is written out row by row. The following is the structure of the table in HTML:
* `<table>`: creates a table.
* `<tr>`: rows.
* `<td>`: columns.
* `<th>`: table headings.
* `colspan`: stretchs the entry across more than one column.
* `rowspan`: stretchs the entry across more than one row.
* `<thead>`: the headings of the table should sit inside it.
* `<tbody>`: the body should sit inside it.
* `<tfoot>`: the footer belongs inside it


