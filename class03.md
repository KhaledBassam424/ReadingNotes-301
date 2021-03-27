# Mustache:

Mustache is a template where we can use it inside Html as a tags instead of 

writing many orders in javascript to handle that. we send to it the data using a 

command in java script Mustach.render(the id or class of the tag which contains 

mustache).

Some specialists call Mustache library a logicless library because it contains no for loops or if statements. 





mustache.js is an implementation of the mustache template system in JavaScript. It is often considered the base for JavaScript templating. And, since mustache supports various languages, we don’t need a separate templating system on the server side.

we apply Mustache inside html  using this form: 


`Mustache.render (“Hello, {{name}}”, { name: “Sherlynn” });`

// returns: Hello, Sherlynn

In the statement above , we see two braces around {{ name }}. This is Mustache syntax to show that it is a placeholder. When Mustache compiles this, it will look for the ‘name’ property in the object we pass in, and replace {{ name }} with the actual value, e,g, “Sherlynn”.



![mustach](images/mustach.png)



> Mustach template example 

```<h4>Product Info: {{name}}</h4>

<ul>
  <li>Product: {{name}}</li>
  <li>Colour: {{colour}}</li>
  <li>Price: ${{price}}</li>
</ul>
```

# Flex 

The flex property is a shorthand property for:

flex-grow
flex-shrink
flex-basis
The flex property sets the flexible length on flexible items.

Note: If the element is not a flexible item, the flex property has no effect.

> display

This defines a flex container; inline or block depending on the given value. It enables a flex context for all its direct children.

``` 
.container {
  display: flex; /* or inline-flex */
}
```
Note that CSS columns have no effect on a flex container.


> flex-direction
the four possible values of flex-direction being shown: top to bottom, bottom to top, right to left, and left to right

This establishes the main-axis, thus defining the direction flex items are placed in the flex container. Flexbox is (aside from optional wrapping) a single-direction layout concept. Think of flex items as primarily laying out either in horizontal rows or vertical columns.

```
.container {
  flex-direction: row | row-reverse | column | column-reverse;
}
``
row (default): left to right in ltr; right to left in rtl
row-reverse: right to left in ltr; left to right in rtl
column: same as row but top to bottom
column-reverse: same as row-reverse but bottom to top