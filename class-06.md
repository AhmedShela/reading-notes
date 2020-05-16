# Understanding The Problem Domain Is The Hardest Part Of Programming

## Why problem domains are hard?

Have you ever tried to put together a jigsaw puzzle that didn’t have any picture on it?  How about one like this one, that has a very similar pattern repeated on it and is double-sided?
The reason why puzzles like this one are so hard, is because you can’t really see what you are trying to build very clearly.  Normally when you put together a jigsaw puzzle you follow steps that might look something like this: 
- Figure out what the major components of the picture are
- Sort the pieces by color or component
- Put together all the border pieces
- Put together each component of the picture from the piles you created

This all breaks down when you don’t have a picture with clear components that you can identify.

* The real world is a messy place.  Many of the problem domains we face as programmers are difficult to understand and look completely different depending on your viewpoint. *.

As programmers, we also are often not given complete information about the problem domain, so we don’t even have the information we need to understand it.

## What can you do about it?

If understanding the problem domain is the hardest part of programming and you want to make programming easier, you can do one of two things:

- Make the problem domain easier
- Get better at understanding the problem domain

* You can often make the problem domain easier by cutting out cases and narrowing your focus to a particular part of the problem. *


# What is ojects ?

Objects group together a set of variables and functions to create a model of a something you would recognize from the real world. In an object, variables and functions take on new names

literal notation is the easiest and most papular way to create objects.
> `var hotel {`
> `name: 'ahmad' ,`
> `rooms: 40 ,`
> `booked: 252 ,`
> `checkAvailableability: function(){`
> `return this.rooms - this.booked ;`
> `}`

## Accessing an object :

> `var hotelName = hotel.name;`


# Document Object Model :

The Document Object Model (DOM) specifies how browsers should create a model of an HTML page and how JavaScript can access and update the contents of a web page while it is in the browser window. 

Each node is an object with methods and properties. Scripts access and update this DOM tree (not the source HTML file). Any changes made to the DOM tree are reflected in the browser. 

Accessing and updating the DOM tree involves two steps: 
- Locate the node that represents the element you want to work with. 
- Use its text content, child elements, and attributes. 
STEP 

The terms elements and element nodes are used interchangeably but when people say the DOM is working with an element, it is actually working with a node that represents that element 

DOM queries may return one element, or they may return a Nodelist, which is a collection of node

There are two ways to select an element from a Nodelist: The item() method and array syntax. Both require the index number of the element you want. 
