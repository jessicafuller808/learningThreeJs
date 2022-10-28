# Learning Three.js
This is me experimenting with animation in JavaScript.

**Link to project:** https://jessicafuller808.github.io/learningThreeJs/

![torusknot](https://user-images.githubusercontent.com/98281798/198721708-34e86d98-e4af-408e-9bbf-56bfcb7ac4f7.png)


## How It's Made:

**Tech used:** HTML, JavaScript, three.Js

The goal is to learn more about animation in JavaScript with the three.js library. This is just following the basic documentation to practice using it.


## Lessons Learned:

* to display an animation a scene, camera, and renderer are required.
* there are different types of renderers than can be used, but WebGL is one of the most common and supported across all modern browsers aside from Opera.
* when setting the size of the renderer it's generally a good idea to use the width and height of the browser window.
* the canvas element is used to display the scene.
* the default coordinates of a rendered object are (0,0,0) so it's important to move the camera out a bit.
* a loop animates the object of the scene by causing the renderer to draw the scene each time the screen is refreshed (mostly 60 fps).
* requestAnimationFrame is better to use than setInterval, mostly because it pauses when the user navigates to another browser tab causing it not to waste processing power and battery.


