# Introducing CSS

CSS allows you to create rules that specify how the content of an element should appear.
For example, you can specify that the background of the page is cream, all paragraphs should
appear in gray using the Arial typeface, or that all level one headings should be in a blue, italic, Times typeface.

## there're 3 ways to add css to HTML

- inline css
- internal css
- external css

### inline css
An inline style may be used to apply a unique style for a single element.
To use inline styles, add the style attribute to the relevant element. The style attribute can contain any CSS property.

### internal css
An internal style sheet may be used if one single HTML page has a unique style.
The internal style is defined inside the `<style>` element, inside the head section.

### external css
With an external style sheet, you can change the look of an entire website by changing just one file!
Each HTML page must include a reference to the external style sheet file inside the `<link>` element, inside the head section.

## associate css style rules with HTML elements

CSS works by associating rules with HTML elements. These rules govern
how the content of specified elements should be displayed. A CSS rule
contains two parts: a selector and a declaration.

|  Selector 	|   Description	|
|---	|---	|
|   Class Selector	|   Matches an element whose class attribute has a value that matches the one specified after the period (or full stop) symbol	|   	
|   ID Selector	|   Matches an element whose id attribute has a value that matches the one specified after the pound or hash symbol	| 
|   Type Selector	|   Matches element names like h1, p, nav	|   	
|   Universal Selector	|   Applies to all elements in the document	| 
|   Descendant Selector	|  Matches an element that is a descendent of another specified element 	|   	



# CSS Colors

The color property allows you to specify the color of text inside an element.
You can specify any color in CSS in one of three ways:

- rgb values
- hex codes
- Color Names


```/* color name */
h1 {
color: DarkCyan;}
/* hex code */
h2 {
color: #ee3e80;}
/* rgb value */
p {
color: rgb(100,100,90);}
```