
# JS Object Literals; The DOM

## Object Literals
what is an object?

The Object literal notation is basically an array of key:value pairs, with a colon separating the keys and values, and a comma after every key:value pair, except for the last, just like a regular array. Values created with anonymous functions are methods of your object. Simple values are properties.

## Declaring methods and properties with Dot notation

Literal Notation is the easiest way to create objects

```
var myObject = new Object();

// properties
	name: = value,
	age: = value,
    color: = value
	myObject.myMethod = function(){
	  //code here
	}
// method
	yourMethod: = function(){
	  //more code
	}
```

## Document Object Model

The Document Object Model (DOM) specifies how browsers should create a model of an HTML page and how JavaScript can access and update the contents of a web page while it is in the browser window.

![Image of DOM JS](https://www.guru99.com/images/JavaScript/javascript8_1.png)


### MAKING A MODEL OF THE HTML PAGE
When the browser loads a web page, it creates a model of the page in memory.
The DOM specifies the way in which the browser should structure this model using a DOM tree.
The DOM is called an object model because the model (the DOM tree) is made of objects.

### ACCESSING AND CHANGING THE HTML PAGE
The DOM also defines methods and properties to access and update each object in this model, which in turn updates what the user sees in the browser.