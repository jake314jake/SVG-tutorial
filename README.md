# SVG-tutorial
Welcome to the SVG Tutorial Repository!
This repository is dedicated to providing comprehensive guidance and resources for mastering Scalable Vector Graphics (SVG), a powerful and versatile XML-based vector image format.
## User Coordinate System and SVG Units
Let’s examine how SVG represents the positions and sizes of objects for drawing.

The default coordinate system in SVG is much the same as in HTML. It works like a two-dimensional x-y plane. The initial SVG coordinate system sets in the initial SVG viewport with the point of origin (0,0) in the top left corner. The positive x-direction being to the right, and the positive y-direction being to the bottom. For specifying (x, y) coordinates, width and height values, you can use cm, mm, in, em, ex, pt, pc, and px. The default SVG units are pixels.
## Hello,SVG
```html
<svg width="100" height="100" xmlns="http://www.w3.org/2000/svg">
  <circle cx="50" cy="50" r="500" stroke="green" stroke-width="4" fill="yellow" />
  <text x="0" y="50" > HELLO ,SVG</text>
</svg>
```
## SVG PATH 
```html
<svg width="100" height="100" xmlns="http://www.w3.org/2000/svg">
   <path d="add path here !" />
</svg>
```
### Move To
M command is used to indicate the start of a new sub-path. It does not draw anything but moves the "pen" to a specified point.
```html
<svg width="100" height="100" xmlns="http://www.w3.org/2000/svg">
  <path d="M 10 10" stroke="black" fill="transparent" />
</svg>

```
### Line To 
L command is used to draw a straight line from the current point to a specified point.
```html
<svg width="100" height="100" xmlns="http://www.w3.org/2000/svg">
  <path d="M 10 10 L 50 50" stroke="black" fill="transparent" />
</svg>
```
### Vertical To , Horizantal To
 the V command is used to draw a vertical line, and the H command is used to draw a horizontal line.
 ```html
<svg width="100" height="100" xmlns="http://www.w3.org/2000/svg">
  <path d="M 10 10 H 50 V 50" stroke="black" fill="transparent" />
</svg>
```
### Close path
 ```html
<svg width="100" height="100" xmlns="http://www.w3.org/2000/svg">
  <path d="M 10 10 L 50 50 L 90 10 Z" stroke="black" fill="transparent" />
</svg>

```

 


