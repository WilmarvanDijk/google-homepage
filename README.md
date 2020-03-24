#Project: HTML/CSS

This project was prepared while goin through The Odin Project (https://www.theodinproject.com/). 
The goal of this project is to counterfeit the Google homepage (https://www.google.nl/). 
Before starting this project it will be helpful to try and master the following skills:

1. **Two ways to move a div around on the page -**
    A div element can be moved with position: relative/absolute/fixed. Then using top, bottom, left, right. For more info see: https://www.w3schools.com/css/css_positioning.asp 
2. **Stick a div onto the bottom or top of the page -**
    There are different methods to do this, they are described below:
    1. position: fixed; (https://www.w3schools.com/howto/howto_js_sticky_header.asp)
    2. There is also different ways to do this. One of them is by using the position:absolute method that can be found through the following links: https://www.freecodecamp.org/news/how-to-keep-your-footer-where-it-belongs-59c6aa05c59c/ or https://stackoverflow.com/questions/643879/css-to-make-html-page-footer-stay-at-bottom-of-the-page-with-a-minimum-height-b 
3. **Identify the background color of an existing webpage -**
    This can be done with the developer tools (F12) in a browser. Then look into the computed area of either the html or body element (most of the time it is declared in on of those elements)
4. **Grab the URL for an image from an existing webpage -**
    You open up developer tools and select the image. Then you look in the elements tab which link is provided with the img element.
5. **Center an element horizontally -**
    This depends on the situation, there are different ways to do it. They are listed below:
    1. **Text or links (inline elements) -** use text-align: center
    2. **Block level element (div element) -** - use margin: 0 auto;
    3. **An image (img element) -** use display:block, margin-left: auto & margin-right:auto.

    See the following [tutorial](https://css-tricks.com/centering-css-complete-guide) for more information.
6. **Identify three ways you can include your CSS styles in a page -**
    There are three ways to include CSS styles in a page, they are described below:
    1. **Inline styling -** a styling is defined within the HTML file by using the style attribute within an element.
    2. **Internal styling -** a styling is definied within the HTML file by using the style element.
    3. **External styling** - a styling is defined in an external file that is linked to within the HTML file by using the link element. The link element gets added within the head tag.
7. **Understand how to use classes and ids to target CSS at specific elements on the page -**
    Include the style within the HTML file by using the class attribute (style="") and select the class within the CSS file by using the class selector (.class). In this example class stands for the name that is given within the quotes of the style attribute.

    Including an ID is done by using the same method. The only difference is that style="" becomes id="" and .class becomes #id. 
8. **Build a very basic form (even if it doesn’t “go” anywhere) -**
    Building a form can be done within the HTML file by using the form element. Within the form element the elements input and label can be used.

Below there is room to describe what skills I have demonstrated once I completed this project (self reflection).





From The Odin Project's [curriculum](http://www.theodinproject.com/courses/web-development-101/lessons/html-css)