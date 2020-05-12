# Links :

Links are the defining feature of the web because they allow you to move from one web page to another — enabling the very idea of browsing or surfing.

> `<a herf="http://www.facebook.com">facebook</a>`

Links are created using the `<a>` element which has an attribute called href. The value of the href attribute is the page that you want people to go to when they click on the link.


## Reletive URLs:

Relative URLs can be used when linking to pages within your own website. They provide a shorthand way of telling the browser where to find your files.

## Open links in a new window:

If you want a link to open in a new window, you can use the target attribute on the opening <a> tag. The value of this attribute should be _blank

## Linking to a specific part of the same page:

> `<a href="#the-member-id-or-class">Arc Shot</a><br /> `

Linking to a spesific part of another page:

> `<a href="page-url/part-ID">Arc Shot</a><br /> `

# Layout :

CSS treats each HTML element as if it is in its own box. This box will either be a block-level box or an inline box.
If one block-level element sits inside another block-level element then the outer box is known as the containing or parent element.
It is common to group a number of elements together inside a `<div>` (or other block-level) element. For example, you might group together all of the elements that form the header of a site (such as the logo and the main navigation). The <div> element that contains this group of elements is then referred to as the containing element.


CSS has the following positioning schemes that allow you to control the layout of a page: normal flow, relative positioning, and absolute positioning. You specify the positioning scheme using the position property in CSS. You can also float elements using the float property.

To indicate where a box should be positioned, you may also need to use box offset properties to tell the browser how far from the top or bottom and left or right it should be placed. (You will meet these when we introduce the positioning schemes on the following pages.)

### position:relative:

Relative positioning moves an element in relation to where it would have been in normal flow.
For example, you can move it 10 pixels lower than it would have been in normal flow or 20% to the right.


### position:absolute

When the position property is given a value of absolute, the box is taken out of normal flow and no longer affects the position of other elements on the page. (They act like it is not there.) 

### position:fixed:

Fixed positioning is a type of absolute positioning that requires the position property to have a value of fixed.

## Screen Size :

Different visitors to your site will have different sized screens that show different amounts of information, so your design needs to be able to work on a range of different sized screens.

## a Liquid layout :

The liquid layout uses percentages to specify the width of each box so that the design will stretch to fit the size of the screen.


# Functions :

Browsers require very detailed instructions about what we want them to do. Therefore, complex scripts can run to hundreds (even thousands) of lines. Programmers use functions, methods, and objects to organize their code. This chapter is divided into three sections that introduce

Functions let you group a series of statements together to perform a specific task. If different parts of a script repeat the same task, you can reuse the function (rather than repeating the same set of statements). 

> `function sayHello() {`
> `document.write('Hello');
> `}`

## calling functions :

> `sayHello();`

