# Padding, Borders, Outlines, and Margins
From the book : CSS: The Definitive Guide, 4th Edition


 - Between the content of an element and its border, we find the padding of an element, and beyond the border, there are outlines and then the margins.
- All document elements generate a rectangular box called the _element box_.




## Remark
 - Overlap can occur if negative margins
 - Default positioning behavior is called 'static'.
 - __*Relative Positioning*__ : They don't influence the layout of surrounding elements.
 - __*Absolute Positioning*__ : 
    . 1) are relative to its first parent that is positioned relative.
    . 2) removes elements from the document flow.

## Remark (less)
- For a non-root element whose position value is **_relative_** or **_static_**, its containing block is formed by the _content edge of the nearest_ block-level, table-cell, or inline-block ancestor box.
- For a non-root element that has a position value of **_absolute_**, its containing block is set to the nearest ancestor (of any kind) that has a position value other than static. This happens as follows:


## To find out
 - width & height don’t apply to inline nonreplaced elements. 






####  Block and Inline Elements

Block-level Elements
```
<div>
<h1> - <h6>
<p>
<form>
```

Inline Elements
```
<span>
<a>
<img>
```

