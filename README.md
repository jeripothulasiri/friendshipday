# friendshipday
**Happy Friendship Day From Siri**
Welcome to a fun and interactive webpage celebrating Friendship Day! When you click the button, you'll see a special message animated in 3D, along with some cool particle effects.

# Features
Date Button: A button displaying today's date.
3D Text Animation: Click the button to see the message "Happy Friendship Day to my dearest friends" and "From Siri" come to life.
Particle Effects: Enjoy the colorful particles that add a festive touch.
Pink Background: Because who doesn't love a cheerful pink background?
# Technologies Used
HTML
CSS
JavaScript
Three.js (for the 3D graphics)
GSAP (for the smooth animations)
# How to Use
Just open the index.html file in your favorite web browser. That's it! No complicated setup needed.

# Prerequisites
Make sure you're using a modern web browser like Google Chrome, Mozilla Firefox, or Microsoft Edge.

# What's Inside
**index.html**: The main file with the structure and content of the webpage.
**CSS**: Inline styles for the button and layout.
**JavaScript**: Inline scripts for setting up the 3D scene, animations, and handling button clicks.
# A Quick Tour of the Code
**HTML**
Contains a button with today's date.
The button has an id of date-button.
**CSS**
The body has a pink background.
The button is styled to be green with white text, centered on the page.
**JavaScript**
Three.js Setup: Initializes the scene, camera, and renderer. Adds lighting, and creates the text and particles.
Text Geometry: Loads a font and creates two lines of text: "Happy Friendship Day to my dearest friends" and "From Siri."
Particles: Creates a group of 1000 tiny, colorful particles.
Animations: Uses GSAP to animate the text and particles when the button is clicked. Includes rotations, scaling, and color changes.
Event Listeners: Handles the button click to start the animation and adjusts the scene when the window is resized.
# Key Functions
init(): Sets up the 3D scene.
animate(): Keeps the particles rotating smoothly.
startAnimation(): Triggers all the animations when the button is clicked.
Dependencies
Three.js: For creating the 3D graphics.
GSAP: For the animation effects.

# Acknowledgments
Thanks to Three.js for the amazing 3D graphics library.
Thanks to GSAP for the smooth animations.
