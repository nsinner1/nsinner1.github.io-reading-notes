HTML

Chapter 16: “Images”

Rather than using the <img> element's align attribute, web page authors are increasingly using the float property to align images. There are two ways that this is commonly achieved:
1: The float property is added to the class that was created to represent the size of the image (such as the small class in our example).
2: New classes are created with names such as align-left or align-right to align the images to the left or right of the page. These class names are used in addition to classes that indicate the size of the image.

repeat
The background image is repeated both horizontally and vertically (the default way it
is shown if the background- repeat property isn't used).
repeat-x
The image is repeated horizontally only (as shown in the first example on the left).
repeat-y
The image is repeated vertically only.
no-repeat
The image is only shown once.
The background-attachment property specifies whether a background image should stay in one position or move as the user scrolls up and down the page. It can have one of two values:
fixed
The background image stays in the same position on the page.
scroll
The background image moves up and down as the user scrolls up and down the page.



Chapter 19: “Practical Information”

As soon as people start coming to your site, you can start analyzing how they found it, what they were looking at and at what point they are leaving. One of the best tools for doing this is a free service offered by Google called Google Analytics.




Video and Audio APIs

The <video> and <audio> elements allow us to embed video and audio into web pages.

Part of the HTML5 spec, the HTMLMediaElement API provides features to allow you to control video and audio players programmatically — for example HTMLMediaElement.play(), HTMLMediaElement.pause(), etc. This interface is available to both <audio> and <video> elements, as the features you'll want to implement are nearly identical.

