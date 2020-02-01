<h2>Domain Modeling</h2>

Domain modeling is the process of creating a conceptual model in code for a specific problem. A model describes the various entities, their attributes and behaviors, as well as the constraints that govern the problem domain. An entity that stores data in properties and encapsulates behaviors in methods is commonly referred to as an object-oriented model.

Here's some tips to follow when building your own domain models.

When modeling a single entity that'll have many instances, build self-contained objects with the same attributes and behaviors.
Model its attributes with a constructor function that defines and initializes properties.
Model its behaviors with small methods that focus on doing one job well.
Create instances using the new keyword followed by a call to a constructor function.
Store the newly created object in a variable so you can access its properties and methods from outside.
Use the this variable within methods so you can access the object's properties and methods from inside.

<h2>HTML Chapter 6</h2>

The <table> element is used to create a table. The contents of the table are written out row by row.

You indicate the start of each row using the opening <tr> tag. (The tr stands for table row.)
It is followed by one or more <td> elements (one for each cell in that row).

The <th> element is used just like the <td> element but its purpose is to represent the heading for either a column or a row. (The th stands for table heading.)

The headings of the table should sit inside the <thead> element.
The body should sit inside the <tbody> element.
The footer belongs inside the <tfoot> element.

