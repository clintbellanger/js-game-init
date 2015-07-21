# js-game-init
Basic framework for my new javascript games

These are the core components that I've grown to use in my HTML5 based javascript games. These games run at a fixed set framerate (default 60fps) where logic and render functions are called once per frame.

Basics on adding game functionality:

* Make a new js file
* The new file should contain a class/object with an init(), logic(), and render() function
* Include the new js file in the index.html header
* Add the init() function in main.js:game_main.init()
* Add the logic() and render() functions to gamestate.js
