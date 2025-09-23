Create a simple shape editor.

Implement the following keystroke commands:
* r: Create a rectangle (size is up to you)
* t: Create a triangle (again, size at your discretion)
* c: A circle
* q: A square

Create a data structure that holds:
* Each shape
* The shape's origin
* The shape's enclosing rectangle (i.e. its outline)
* The shape's color

Allow the user to select a shape with the mouse:
* On click, find the shape that's nearest to the mouse location.
* Do NOT worry about making that search efficient. There's an entire field of computational geometry dedicated to that.
* Once a shape is selected, make it the "current shape".
* Identify the current shape using something clever with CSS. For example a border, or another shape drawn *behind* it (like a larger yellow rectangle)

Commands:
* m: Move the current shape. The next mouse click location becomes the new origin of the shape.
* 1: Make the shape red
* 2: Make the shape blue
* 3: Make the shape green
* +: Increase the shape size by 10%
* -: Decrease the shape size by 10%
  
