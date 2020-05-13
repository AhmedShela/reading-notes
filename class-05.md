# Images :

There are many reasons why you might want to add an image to a web page: you might want to include a logo, photograph, illustration, diagram, or chart.

A picture can say a thousand words, and great images help make the difference between an average-looking site and a really engaging one.

## Storing images in your site:

If you are building a site from scratch, it is good practice to create a folder for all of the images the site uses.

As a website grows, keeping images in a separate folder helps you understand how the site is organized. Here you can see an example of the files for a website; all of the images are stored in a folder called images.

On a big site you might like to add subfolders inside the images folder. For example, images such as logos and buttons might sit in a folder called interface, product photographs might sit in a page called products, and images related to news might live in a folder called news.

## Adding Images `<img>` :

To add an image into the page you need to use an <img> element. This is an empty element (which means there is no closing tag). It must carry the following two attributes:

* `src`: This tells the browser where it can find the image file. This will usually be a relative URL pointing to an image on your own site. (Here you can see that the images are in a child folder called images — relative URLs were covered on pages 83-84). 
* `alt`: This provides a text description of the image which describes the image if you cannot see it.
* `title` : You can also use the title attribute with the <img> element to provide additional information about the image. Most browsers will display the content of this attribute in a tootip when the user hovers over the image

## Three rouls for creating images :

- saVe Images In the rIght format
- saVe Images at the rIght sIze
- use the CorreCt resolutIon

## Figure and figure caption:

* `<figure>` :
Images often come with captions. HTML5 has introduced a new <figure> element to contain images and their caption so that the two are associated. 
You can have more than one image inside the <figure> element as long as they all share the same caption.
* `<figurecaption>` :
The <figcaption> element has been added to HTML5 in order to allow web page authors to add a caption to an image.
Before these elements were created there was no way to associate an <img> element with its caption.

# Color 

* rgb values 
These express colors in terms of how much red, green and blue are used to make it up. For example: rgb(100,100,90)
* hex Codes 
These are six-digit codes that represent the amount of red, green and blue in a color, preceded by a pound or hash # sign. For example: #ee3e80
* Color names 
There are 147 predefined color names that are recognized by browsers. For example: DarkCyan

## background-color:

CSS treats each HTML element as if it appears in a box, and the background-color property sets the color of the background for that box.
You can specify your choice of background color in the same three ways you can specify foreground colors: RGB values, hex codes, and color names (covered on the next page).

*Every color on a computer screen is created by mixing amounts of red, green, and blue. To find the color you want, you can use a color picker.*

# Test 

*The formatting of your text can have a significant effect on how readable your pages are. As we look through these properties I will also give you some design tips on how to display your type.*

## `font-family`

The font-family property allows you to specify the typeface that should be used for any text inside the element(s) to which a CSS rule applies.
The value of this property is the name of the typeface you want to use.

## `font-size`

The font-size property enables you to specify a size for the font. There are several ways to specify the size of a font. 

## `font-weight`

The font-weight property allows you to create bold text. 

## `font-style`

If you want to create italic text, you can use the font-style property.


