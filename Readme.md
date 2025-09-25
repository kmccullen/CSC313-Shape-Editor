Create a simple shape editor.

Implement the following keystroke commands:
* r: Create a rectangle (size is up to you)
* c: A circle
* q: A square (special rectangle)

Create a data structure that holds:
* Shape type (i.e. name, like "circle")
* Shape origin (x and y) ... note the actual attributes will depend on the shape type, cx/cy for circles, rx/ry for rectangles.
* Other required attribute (like "r" for circle radius)
* Shape's fill color
* Shape's ID (recommend using "id"+n, where n is the nth shape created)

Allow the user to select a shape with the mouse:
* On click, find the shape that's nearest to the mouse location.
* Do NOT worry about making that search efficient. There's an entire field of computational geometry dedicated to that.
* Once a shape is selected, make it the "current shape".
* Identify the current shape by making it blink for two seconds (250 ms on/off)

Commands:
* m: Move the current shape. The next mouse click location becomes the new origin of the shape.
* 1: Make the shape red
* 2: Make the shape blue
* 3: Make the shape green
* +: Increase the shape size by 10%
* -: Decrease the shape size by 10%
  
