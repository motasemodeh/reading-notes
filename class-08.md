# HTML Tables
A table represents information in a grid format. Grids allow us to understand complex data by referencing information on two axes.
Each block in the grid is referred to as a table cell. In HTML a table is written out row by row.

## Basic Table structure

`<table>`
The `<table>` element is used to create a table. The contents of the table are written out row by row.
`<tr>`
You indicate the start of each row using the opening `<tr>` tag. (The tr stands for table row.)
It is followed by one or more
`<td>` elements (one for each cell in that row). At the end of the row you use a closing `</tr>` tag.
`<td>`
Each cell of a table is represented using a `<td>`
element. (The td stands for table data.) At the end of each cell you use a closing `</td>` tag. Some browsers automatically draw lines around the table and/or the individual cells. You will learn how to control the borders of tables using CSS on pages 309-312 and 337-340.

`<th>`
The `<th>` element is used just like the `<td>` element but its purpose is to represent the heading for either a column or a row.


|  Head 	|   head	|
|---	|---	|
|   CELL	|   CELL	|   	
|   CELL	|   CELL	| 
|   CELL	|   CELL	|



# Creating an object: constructor notation

the new keyword can be used to create an empty object and then you can add properties and methods.

`var hotel = new object();`

First, we need the keyword new and the object() constructor function after creating the object you can add properties to it using dot notation

please note that each statemnt that adds a propertiy or method ends ith semicolon `;`

## updating an object

to update the value of an object you need to use dot notation or bracket notation.

`hotel.name = 'Motasem';`



![Image of Object update](img/updating-objects.png)



## CREATING OBJECTS USING CONSTRUCTOR SYNTAX


```
var hotel = new Object();
hotel.name= 'Park';
hotel.rooms = 120;
hotel .booked = 77;
hotel .checkAvailability = function()
return this . rooms - this.booked;
} ;
JAVASCRIPT
var elName = document.getElementByid('hotelName');
elName.textContent = hotel . name;
var elRooms = document .getElementByid('rooms');
elRooms .textContent = hotel .checkAvailability(};
```

## ADDING AND REMOVING PROPERTIES

Once you have created an object (using literal or constructor notation), you can add new properties to it.
You do this using the dot notation.

```
var hotel = {
name : 'Park' ,
rooms : 120,
booked : 77.
} ;
hotel .gym = t rue;
hotel .pool = fal se;
delete hotel .booked;
var elName = document .getEl ementByld('hotelName ' );
elName.textContent = hotel . name;
var el Pool = document .getElementByid ('pool ') ;
elPool.cl assName = ' Pool: ' + hotel. pool ;
var elGym = document .getEl ementByld('gym ' };
elGym.className = 'Gym: ' + hotel .gym;
```

## this Keyord

The keyword this is commonly used inside functions and objects.
Where the function is declared alters what this means. It always refers to one object, usually the object in which the function operates.