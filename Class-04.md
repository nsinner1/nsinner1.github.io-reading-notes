<h2>HTML Chapter 4</h2>
Links are created using the <a> element. Users can click on anything between the opening <a> tag and the closing </a> tag. You specify which page you want to link to using the href attribute.
The text between the opening <a> tag and closing </a> tag is known as link text.
Links are created using the <a> element which has an attribute called href. The value of the href attribute is the page that you want people to go to when they click on the link.
Relative URLs can be used when linking to pages within your own website. They provide a shorthand way of telling the browser where to find your files.
To create a link that starts up
the user's email program and addresses an email to a specified email address, you use the <a> element. 
If you want a link to open in a new window, you can use the target attribute on the opening <a> tag. The value of this attribute should be _blank.

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
Fixed width layout designs do not change size as the user increases
or decreases the size of their browser window. Measurements tend to be given in pixels.
Liquid layout designs stretch and contract as the user increases or decreases the size of their browser window. They tend to use percentages.
To create a fixed width layout, the width of the main boxes on a page will usually be specified in pixels (and sometimes their height, too).
The liquid layout uses percentages to specify the width of each box so that the design will stretch to fit the size of the screen.


<h2>JS Chapter 3</h2>

FUNCTIONS & METHODS
Functions consist of a series of statements
that have been grouped together because they perform a specific task.
A method is the same as a function, except methods are created inside (and are part of) an object.

OBJECTS
In Chapter 1you saw that
programmers use objects to create models of the world using data, and that objects are made up of properties and methods. In this section, you learn how to create your own objects using JavaScript.

BUILT-IN OBJECTS
The browser comes with a set of objects that act like a toolkit for creating interactive web pages. This section introduces you to a number of built-in objects, which you will then see used throughout the rest of the book.

Functions let you group a series of statements together to perform a specific task. If different parts of a script repeat the same task, you can reuse the function (rather than repeating the same set of statements).

To create a function, you give it a name and then write the statements needed to achieve its task inside the curly braces, function declaration. 

Having declared the function, you can then execute all of the statements between its curly braces with just one line of code, calling the function. 

Sometimes a function needs specific information fo perform its task. In such cases, when you declare the function you give it parameters. 

When you call a function that has parameters, you specify the values it should use in the parentheses that follow its name, arguments. 

Expressions produce a value. They can be used where values are expected. If a function is placed where a browser expects to see an expression,
(e.g., as an argument to a function), then it gets treated as an expression.

The location where you declare a variable will affect where it can be used within your code. If you declare it within a function, it can only be used within that function. This is known as the variable's scope.

Global variables use more memory. The browser has to remember them for as long as the web page using them is loaded. Local variables are only remembered during the period of time that a function is being executed.

<h1>6 Reasons for Pair Programming</h2>

The Driver is the programmer who is typing and the only one whose hands are on the keyboard. Handling the “mechanics” of coding, the Driver manages the text editor, switching files, version control, and—of course writing—code. The Navigator uses their words to guide the Driver but does not provide any direct input to the computer. The Navigator thinks about the big picture, what comes next, how an algorithm might be converted in to code, while scanning for typos or bugs. The Navigator might also utilize their computer as a second screen to look up solutions and documentation, but should not be writing any code.

Pair programming touches on all four skills: developers explain out loud what the code should do, listen to others’ guidance, read code that others have written, and write code themselves.
1. Greater efficiency
2. Engaged collaboration
3. Learning from fellow students
4. Social skills
5. Job interview readiness
6. Work environment readiness