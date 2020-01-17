<h2>Chapter 3</h2>
The ordered list is created with the <ol> element.

The unordered list is created with the <ul> element.

Each item in the list is placed between an opening <li> tag and a closing </li> tag. (The li stands for list item.)

The definition list is created with the <dl> element and usually consists of a series of terms and their definitions.
Inside the <dl> element you will usually see pairs of <dt> (term being defined) and <dd> (contain definition) elements.

<h2>Chapter 13</h2>
The most popular ways to specify the size of a box are
to use pixels, percentages, or ems. Designers have recently started to use percentages and ems more for measurements as they try to create designs that are flexible across devices which have different-sized screens.

Some page designs expand and shrink to fit the size of the user's screen. In such designs, the min-width property specifies the smallest size a box can be displayed at when the browser window is narrow, and the max-width property indicates the maximum width a box can stretch to when the browser window is wide. This can also be done with height. 

The overflow property tells the browser what to do if the content contained within a box is larger than the box itself. It can have one of two values:
Hidden: This property simply hides any extra content that does not fit in the box.
Scroll: This property adds a scrollbar to the box so that users can scroll to see the missing content.

Boarder: Every box has a border (even if it is not visible or is specified to be 0 pixels wide). The border separates the edge of one box from another.
    Properties: thin, medium, thick, border-top-width, border-right-width, border-bottom-width, border-left-width
    Style: solid, dotted, dash, etc
    Color: border-top-color, border-right-color, border-bottom-color, border-left-color
Margin: Margins sit outside the edge
of the border. You can set the width of a margin to create a gap between the borders of two adjacent boxes.
    Properties: margin-top, margin-right, margin-bottom, margin-left
Padding: Padding is the space between the border of a box and any content contained within it. Adding padding can increase the readability of its contents.
    Properties: padding-top, padding-right, padding-bottom, padding-left

If you want to center a box on the page (or center it inside the element that it sits in), you can set the left-margin and right-margin to auto.
In order to center a box on the page, you need to set a width for the box (otherwise it will take up the full width of the page).

The display property allows you to turn an inline element into a block-level element or vice versa, and can also be used to hide an element from the page.
    Properties: inline, block, inline-block, none

The border-image property applies an image to the border of any box. It takes a background image and slices it into nine pieces.

The box-shadow property allows you to add a drop shadow around a box. 

Create rounded corners on any box, using a property called border-radius. The value indicates the size of the radius in pixels.
    Properties: border-top-right-radius, border-bottom-right-radius, border-bottom-left-radius, border-top-left-radius

<h2>Chapter 4</h2>
A switch statement starts with a variable called the switch value. Each case indicates a possible value for this variable and the code that should run if the variable matches that value.  
You have a default option that is run if none of the cases match.
If a match is found, that code is run; then the break statement stops the rest of the switch statement running (providing better performance than multiple i f statements).  