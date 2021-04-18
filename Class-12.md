# Charts

In order to creat a chart you need first to download the [Chart.js](https://www.chartjs.org/docs/latest/getting-started/installation.html), and then you set the html structure and add the script to it .

You can add a new chart by `new Chart.chartType`, you will need to identify the vaues in an array.

# `<canvas> </canvas>`

This is an HTML element that is quiet similar to `<img>`,`<audio>` or `<video>`. You have to provide a useful fallback content to be displayed or accessed browsers.

You may specify it's width and height , if not it'll be set automatically to be 300x wide and 150px high.

## Drawing shapes using canvas

First you must specify the gird dimensions (width and height);

To draw a rectangle:

* `fillRect(x, y, width, height)` Draws a filled rectangle.
* `strokeRect(x, y, width, height)` Draws a rectangular outline.
* `clearRect(x, y, width, height)` Clears the specified rectangular area, making it fully transparent.

To draw paths:

* `beginPath()` Creates a new path. Once created, future drawing commands are directed into the path and used to build the path up.
* `Path methods` Methods to set different paths for objects.
* `closePath()` Adds a straight line to the path, going to the start of the current sub-path.
* `stroke()` Draws the shape by stroking its outline.
* `fill()` Draws a solid shape by filling the path's content area.

To draw circles and arcs:

* `arc(x, y, radius, startAngle, endAngle, counterclockwise)` Draws an arc which is centered at (x, y) position with radius r starting at startAngle and ending at endAngle going in the given direction indicated by counterclockwise (defaulting to clockwise).
* `arcTo(x1, y1, x2, y2, radius)` Draws an arc with the given control points and radius, connected to the previous point by a straight line.
 
 You can draw so many other shapes like curves andn lines and you can creat shapes by combining them, check the below URLs for more information.


 ## Applying styles

* `fillStyle = color` Sets the style used when filling shapes.
* `strokeStyle = color` Sets the style for shapes' outlines.
* `globalAlpha = transparencyValue` values between 0-1.
* Applying `lineWidth` ,`lineCap`, `lineJoin`, `miterLimit`, `lineDashOffset` values to style lines.
* Gradients : `createLinearGradient(x1, y1, x2, y2)`, 
`createRadialGradient(x1, y1, r1, x2, y2, r2)`, `createConicGradient(angle, x, y)`
* Creat patterns `createPattern(image, type)` and specify the repetition.


## Drawing and Styling texts

* `fillText(text, x, y [, maxWidth])`
* `strokeText(text, x, y [, maxWidth])`
*  You can edit the `font` size, `text-align` , `textBaseline` and text's `direction`.




References:

* [URL](https://www.webdesignerdepot.com/2013/11/easily-create-stunning-animated-charts-with-chart-js/)
* [URL]https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Basic_usage)
* [URL](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Drawing_shapes)
* [URL](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Applying_styles_and_colors)
* [URL](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Drawing_text)