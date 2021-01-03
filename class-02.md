# Text

## Structural Markup

they are elements that describe headings and paragraphs 

### Headings
in HTML we have six levels of headings
`<h1>` - `<h6>`

### Paragraphs
`<p>`
To create a paragraph, surround the words that make up the paragraph with an opening `<p>` tag and closing `</p>` tag.

## Semantic markup
There are some text elements that are not intended to affect the structure of your web pages, but they do add extra information to the pages — they are known as semantic markup

### Strong & Emphasis
`<strong>`
The use of the `<strong>` element indicates that its content has strong importance.

`<em>`
The `<em>` element indicates emphasis that subtly changes the meaning of a sentence.

### Quotations

`<blockquote>`
The `<blockquote>` element is used for longer quotes that take up an entire paragraph. Note how the `<p>` element is still used inside the `<blockquote>` element.

# Introducing CSS

## What CSS does

CSS can style almost any HTML tag that creates a visible element on the page, including all the HTML tags used to create headings, paragraphs, links, images, lists, and tables t.

## How CSS Work

CSS works by associating rules with HTML elements. These rules govern how the content of specified elements should be displayed. A CSS rule contains two parts: a selector and a declaration.

![Image of CSS Declration](img/css-selector.jpg)

Selectors indicate which element the rule applies to.

Selectors can be the following:

|  Selector 	|   Description	|
|---	|---	|
|   Class Selector	|   Matches an element whose class attribute has a value that matches the one specified after the period (or full stop) symbol	|   	
|   ID Selector	|   Matches an element whose id attribute has a value that matches the one specified after the pound or hash symbol	| 
|   Type Selector	|   Matches element names like h1, p, nav	|   	
|   Universal Selector	|   Applies to all elements in the document	| 
|   Descendant Selector	|  Matches an element that is a descendent of another specified element 	|   


# Basic JavaScript Instructions

## Statements

A script is a series of instructions that a computer can follow one-by-one.
Each individual instruction or step is known as a statement.
Statements should end with a semicolon.

Example:

`var today= new Date();`


## COMMENTS

You should write comments to explain what your code does. They help make your code easier to read and understand. This can help you and others who read your code.

This how comments look like in javascript

```/* This script displays a greeting to the user based upon the current time.
It is an example from JavaScript & jQuery book */
```


`// Display the appropriate greeting based on the current time`



## Variables

A script will have to temporarily store the bits of information it
needs to do its job. It can store this data in variables.

we use variables to "remember" the values for width and height. (This also illustrates how a scrip( contains very explicit instructions about
exactly what you want the computer to do.) You can compare variables to short-term memory, because once you leave the page, the browser will
forget any information it holds.



# Decisions and Loops

## Decision making
In JS, the code needs to make decisions and carry out actions accordingly depending on different inputs. There are two components to a decistion
1. Evaluation of a condation
2. a conditional statement says what to do in  a given situation

### Comparison Operators
Comparison operators are used in logical statements to determine equality or difference between variables or values.


|  Operator 	|   Description	|  Comparing	|
|---	|---	|---	|---	|
|   ==	|   	equal to	|   x == 8  |   false   |
|  ===	|   equal value and equal type	|  x === "10"   |   false    |
|  !=   |   not equal	|  x != 8   |  	true    |
|  !==  |   not equal value or not equal type	|   x !== 8  |   true   |
|   >   |  	greater than	|  x > 8   |   false   |
|   <   |   less than	|  x < 8   |   true   |
|   >=  |  	greater than or equal to	|   x >= 8  |   false   |
|   <=  |   less than or equal to	|  x <= 8   |   true   |