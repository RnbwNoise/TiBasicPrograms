# SetWnd.85p

Sets graphing window that will have equal physical size of one data unit along both x- and y-axis -- i.e. a window that will not appear stretched or compressed. A window like this is essential for identifying geometric properties of shapes and curves by a taking quick look at the graph. For example, for determining whether two curves are perpendicular, or whether a given shape is a circle or a square.

Input:

* (`x`, `y`) is a point that will be in the center of the screen.
* `scale` is the magnification of the graph, particularly, the number of pixels along the x-axis that will be used to represent a single unit on the graph. This number will be adjusted for the y-axis to compensate the [pixel aspect ratio of the calculator](http://www2.math.ou.edu/~amiller/ti85/display.htm).