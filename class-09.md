# Layout

## Controll ing the Position of Elements

`position: static;`

In normal flow, each block-level element sits on top of the next one. Since this is the default way in which browsers treat HTML elements, you do not need a CSS property to indicate that elements should appear in normal flow, but the syntax would be:


`position:relative`

Relative positioning moves an element in relation to where it would have been in normal flow. For example, you can move it 10 pixels lower than it would have
been in normal flow or 20% to the right. You can indicate that an element should be relatively positioned using the position property with a value of relative.


`position:absolute`

When the position property is given a value of absolute,
the box is taken out of normal flow and no longer affects the position of other elements on the page. (They act like it is not there.) The box offset properties (top or bottom and left or right) specify where the element should appear in relation to its containing element.

`position:fixed`

Fixed positioning is a type of absolute positioning that requires the position property to have a value of fixed. It positions the element in relation to the browser window. Therefore, when a user scrolls down the page, it stays in the
exact same place. It is a good idea to try this example in your browser to see the effect.



## Floating Elements

The float property allows you to take an element in normal flow and place it as far to the left or right of the containing element as possible. Anything else that sits inside the containing element will flow around the element that is floated.