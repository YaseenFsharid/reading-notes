# Charts
_creating chart in html is done by :_
+ **using chart construter of objects:**
1. type example **'line'**
2.  data object _that contains the chart data properites_
3. and the rest of requier for creating objects like 
 + **options** 
 + **scales**
 + **beginAtZero = true**

 ## The < canvas > element 
 _The < canvas> element differs from an < img> tag in that, like for < video>, < audio>, or < picture> elements, it is easy to define some fallback content_

 ## The grids
 _Drowing rectangular_
+ fillRect(x, y, width, height)
+ _Draws a filled rectangle._
+ strokeRect(x, y, width, height)
+ Draws a rectangular outline.
_clearRect(x, y, width, height)_

### Drowing path 
1. First, you create the path.
2. Then you use drawing commands to draw into the path.
3. Once the path has been created, you can stroke or fill the path to render it.
**Here are the functions used to perform these steps:**

+ beginPath()
_Creates a new path. Once created, future drawing commands are directed into the path and used to build the path up._
+ Path methods
_Methods to set different paths for objects._
+ closePath()
_Adds a straight line to the path, going to the start of the current sub-path._
+ stroke()
_Draws the shape by stroking its outline._
+ fill()
_Draws a solid shape by filling the path's content area_

### Lines
**For drawing straight lines, use the lineTo() method.**
lineTo(x, y)
Draws a line from the current drawing position to the position specified by x and y.
This method takes two arguments, x and y, which are the coordinates of the line's end point. The starting point is dependent on previously drawn paths, where the end point of the previous path is the starting point for the following, etc. The starting point can also be changed by using the moveTo() method.

### Colors
Up until now we have only seen methods of the drawing context. If we want to apply colors to a shape, there are two important properties we can use: fillStyle and strokeStyle.

+ fillStyle = color
Sets the style used when filling shapes.
+ strokeStyle = color
Sets the style for shapes' outlines.

### Transparency
In addition to drawing opaque shapes to the canvas, we can also draw semi-transparent (or translucent) shapes. This is done by either setting the globalAlpha property or by assigning a semi-transparent color to the stroke and/or fill style.

globalAlpha = transparencyValue

