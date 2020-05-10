# text

## headings:

* **<h1>** is used for main headings

* **<h2>** is used for subheadings

* **<h3>** element is used, and so on

## Paragraphs:

* **<p>** To create a paragraph, surround the words that make up the paragraph with an opening <p> tag and closing </p> tag.

* **<b>** By enclosing words in the tags <b> and </b> we can make characters appear bold.

* **<i>** By enclosing words in the tags <i> and </i> we can make characters appear italic

## suPerscriPT & suBscriPT:

* **<sub>** The <sup> element is used to contain characters that should be superscript such as the suffixes of dates or mathematical concepts like raising a number to a power such as 22. 

## White Space 

In order to make code easier to read, web page authors often add extra spaces or start some elements on new lines.
When the browser comes across two or more spaces next to each other, it only displays one space. Similarly if it comes across a line break, it treats that as a single space too. This is known as **white space collapsing**.

## sTrong & emPHasis:

* **<Strong>** The use of the <strong> element indicates that its content has strong importance. For example, the words contained in this element might be said with strong emphasis.

* **<em>** The <em> element indicates emphasis that subtly changes the meaning of a sentence.

## aBBreViaTions & acronyms:

* **<abbr>** If you use an abbreviation or an acronym, then the <abbr> element can be used. A title attribute on the opening tag is used to specify the full term.

## auTHor deTails

* **<adress>** The <address> element has quite a specific use: to contain contact details for the author of the page.


# Understanding Css:

*The key to understanding how CSS works is to imagine that there is an invisible box around every HTML element*
*CSS allows you to create rules that control the way that each individual box (and the contents of that box) is presented.*

## using external css

* **<link>** 
The <link> element can be used in an HTML document to tell the browser where to find the CSS file used to style the page. It is an empty element (meaning it does not need a closing tag), and it lives inside the <head> element. It should use three attributes:
**herf**: href This specifies the path to the CSS file (which is often placed in a folder called css or styles).
**type**:This attribute specifies the type of document being linked to. The value should be text/css.
**ref**:This specifies the relationship between the HTML page and the file it is linked to. The value should be stylesheet when linking to a CSS file.

## using the enternal css:

* **<style>**
You can also include CSS rules within an HTML page by placing them inside a <style> element, which usually sits inside the <head> element of the page. 
The <style> element should use the type attribute to indicate that the styles are specified in CSS. The value should be text/ css.

## How Css rules cascade

If there are two or more rules that apply to the same element, it is important to understand which will take precedence. 

*Last rule* If the two selectors are identical, the latter of the two will take precedence. Here you can  see the second i selector takes precedence over the first.

*Specificity* If one selector is more specific than the others, the more specific rule will take precedence over more general ones. In this example:
h1 is more specific than * p b is more specific than p p#intro is more specific than p

*important* You can add !important after any property value to indicate that it should be considered more important than other rules that apply to the same element.


# JAva Script:

## Statement:
A script is a series of instructions that a computer can follow one-by-one. Each individual instruction or step is known as a statement. Statements should end with a semicolon. 

> `var greeting = "Hello World"`

#### **JAva script is case sensetive wich means UserName not the same of username

## Comments :

You should write comments to explain what your code does. They help make your code easier to read and understand. This can help you and others who read your code

> `/* Thi s script displays a greeting to the user based upon the current time. It is an example from JavaScript & jQuery book */`

## Arrays :

An array is a special type of variable. It doesn't just store one value; it stores a list of values. 
You should consider using an array whenever you are working with a list or a set of values that are related to each other. 
For example, an array can be suited to storing the individual items on a shopping list because it is a list of related items. 

### CREATING AN ARRAY :

> `var colors; colors ['white', 'black', 'custom'];`

### Accessing & Changing Values in an Array:

> // Create the array 
> var colors = ['white', 'black' , 'custom']; 
> //update the third item in the array
> colores[2] = 'being';
> //Get the element with an id of colors
> var el = document.getElementById('colors');
> Replace with third item from the array
> el.textContent = colors[2];

### Expressions :

An expression evaluates into (results in) a single value. Broadly speaking there are two types of expressions. 

# Dicision & Loops :

## Dexision Making :

> `if(condition){`
> `some code;`
> `}`