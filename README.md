# Quicklook.js

The jsgradient plugin
The easiest way to implement a gradient is by calling the gradientList() function, specifying the start color, end color and list element you want to style like so:

    jsgradient.gradientList('#07E3F2', '#155994', '#demo');

You can pass in the colors in the following formats: ‘fff’, ‘#fff’, ‘ffffff’ or ‘#ffffff’. The list element can also be passed in as a string e.g. ‘#demo’ or as a jquery object e.g. $(‘#demo’);

You can also call the generateGradient() function as the example below shows and this will return the array of hex colors for you do use however you like.

    jsgradient.generateGradient('#07E3F2', '#155994', 10);