<h2>HTML Chapter 15</h2>

If one block-level element sits inside another block-level element then the outer box is known as the containing or parent element.

CSS has the following positioning schemes that allow you to control the layout of a page: normal flow, relative positioning, and absolute positioning.

To indicate where a box should be positioned, you may also need to use box offset properties to tell the browser how far from the top or bottom and left or right it should be placed. 

Relative positioning moves an element in relation to where it would have been in normal flow.

When the position property is given a value of absolute, the box is taken out of normal flow and no longer affects the position of other elements on the page. (They act like it is not there.)

Fixed positioning is a type
of absolute positioning that requires the position property to have a value of fixed.

If you want to control which element sits on top, you can use the z-index property. Its value is a number, and the higher the number the closer that element is to the front. For example, an element with a z-index of 10 will appear over the top of one with a z-index of 5.

The float property allows you to take an element in normal flow and place it as far to the left or right of the containing element as possible.

Fixed width layout designs do not change size as the user increases or decreases the size of their browser window. Measurements tend to be given in pixels.

Liquid layout designs stretch and contract as the user increases or decreases the size of their browser window. They tend to use percentages.

To create a fixed width layout, the width of the main boxes on a page will usually be specified in pixels (and sometimes their height, too).

The liquid layout uses percentages to specify the width of each box so that the design will stretch to fit the size of the screen.
