# 3D-Cube
* This is a simple 3D cube project that allows the user to rotate the cube using their mouse.
* The project is built using HTML, CSS, and JavaScript.

## HTML
* The HTML code defines the structure of the project. 
* There is a container element that wraps the cube element, which has six child elements representing each face of the cube. 
* Each face has a unique class name and text content indicating which face it is.

## CSS
* The CSS code defines the styles for the project. 
* The container has a margin, width, height, and perspective properties. 
* The cube has position, width, height, user-select, cursor, transition, and transform-style properties. 
* Each face has position, width, height, text-align, line-height, font-size, font-weight, color, opacity, and transform properties.

## JavaScript
* The JavaScript code allows the user to rotate the cube using their mouse. 
* There are event listeners for mouse down, mouse up, and mouse move events. 
* The onMouseDown function sets a flag to indicate that the mouse is being dragged and saves the initial mouse position. 
* The onMouseUp function clears the dragging flag. 
* The onMouseMove function calculates the change in mouse position and updates the current rotation of the cube based on this change. 
* The updateCubeRotation function updates the transform property of the cube element to apply the current rotation.

## Files
- The project contains the following files:

   - index.html: The HTML code for the project.
   - style.css: The CSS code for the project.
   - script.js: The JavaScript code for the project.

## Contributing
 * If you would like to contribute to the project, feel free to create a pull request with your changes. Any contributions are welcome!
