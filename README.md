Writing a displacement shader in A-Frame
=========================

This example shows how to write custom shaders (GLSL) and use them to create effects in A-Frame / three.js / WebGL.

Click `Show` in the header to see the demo.

Features
------------

The grid-glitch shader, defined by `shader-grid-glitch.js`
- Component data schema that shows how to pass in color, and utilize time.
- Basic vertex shader that provides the varying UV coordinate to the fragment shader.
- Fragment shader that uses the supplied UV, color and time values.

The webpage `index.html` has a basic scene with a sphere using the grid-glitch shader.