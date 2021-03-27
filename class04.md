# CSS Grid Layout : 

css grid divide our page into many equal or unequal parts based on instructions given to it.

it divides the page in terms of size, position, and layer, between parts of a control built from HTML primitives.

Like tables, grid layout enables to align elements into columns and rows. However, many more layouts are either possible or easier with CSS grid than they were with tables. For example, a grid container's child elements could position themselves so they actually overlap and layer, similar to CSS positioned elements. 

> Example on usage grid : 

```.wrapper {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 10px;
  grid-auto-rows: minmax(100px, auto);
}
.one {
  grid-column: 1 / 3;
  grid-row: 1;
}
.two {
  grid-column: 2 / 4;
  grid-row: 1 / 3;
}
.three {
  grid-column: 1;
  grid-row: 2 / 5;
}
.four {
  grid-column: 3;
  grid-row: 3;
}
.five {
  grid-column: 2;
  grid-row: 4;
}
.six {
  grid-column: 3;
  grid-row: 4;
}
```

> Grid layout way has different methods can be applicable : 


1. grid-area

2. grid-auto-columns

3. grid-auto-flow

4. grid-auto-rows

5. grid-column-end

6. grid-column-start

7. grid-column

8. grid-row-end

9. grid-row-start

10. grid-row

11. grid-template-areas

12. grid-template-columns

13. grid-template-rows

14. grid-template

> A grid column :

is a vertical track in a CSS Grid Layout, and it defines the space between two vertical grid lines. It is defined by the grid-template-columns property or in the shorthand grid or grid-template properties.

In addition, columns may be created in the implicit grid when items are placed outside of columns created in the explicit grid. These columns will be auto-sized by default, or can have a size specified with the grid-auto-columns property.

When working with alignment in CSS Grid Layout, the axis down which columns run is known as the block, or column, axis. 

## Regular Expressions : 

Regular expressions (regex or regexp) are extremely useful in extracting information from any text by searching for one or more matches of a specific search pattern (i.e. a specific sequence of ASCII or unicode characters).
Fields of application range from validation to parsing/replacing strings, passing through translating data to other formats and web scraping.
One of the most interesting features is that once you’ve learned the syntax, you can actually use this tool in (almost) all programming languages ​​(JavaScript, Java, VB, C #, C / C++, Python, Perl, Ruby, Delphi, R, Tcl, and many others) with the slightest distinctions about the support of the most advanced features and syntax versions supported by the engines).

# Examples and Explanations: 

1.  > Anchors — ^ and $

```
^The        matches any string that starts with The -> Try it!
end$        matches a string that ends with end
^The end$   exact string match (starts and ends with The end)
roar        matches any string that has the text roar in it
```

2. > Quantifiers — * + ? and {}

```
abc*        matches a string that has ab followed by zero or more c -> Try it!
abc+        matches a string that has ab followed by one or more c
abc?        matches a string that has ab followed by zero or one c
abc{2}      matches a string that has ab followed by 2 c
abc{2,}     matches a string that has ab followed by 2 or more c
abc{2,5}    matches a string that has ab followed by 2 up to 5 c
a(bc)*      matches a string that has a followed by zero or more copies of the sequence bc
a(bc){2,5}  matches a string that has a followed by 2 up to 5 copies of the sequence bc
```
