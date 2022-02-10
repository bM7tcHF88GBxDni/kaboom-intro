
# Introduction to Kaboom JS

This repository has been setup so you can begin your Kaboom JS game dev adventure!

We will provide the basic guide to using Kaboom and provide the best resources we found to develop your game.

## Using Kaboom JS with VS Code
Kaboom has a NPM module but it can be tricky to use it as it also requires ESBuild or Webpack. Fortunately it is very easy to use Kaboom's CDN (Content Delivery Network) URL using just two files like so:

index.html
```html
<head>
    <script src="https://unpkg.com/kaboom/dist/kaboom.mjs"></script>
    <script type="module" src="./main.js"></script>
</head>
```

main.js
```js
import kaboom from "https://unpkg.com/kaboom/dist/kaboom.mjs";

kaboom({
  global: true,
  fullscreen: true,
  scale: 1,
  debug: true,
});
```
Once you have this set up, install this Live Server VS Code extension:
https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer

Run the index.html using Live Server by pressing the blue "Go Live" button on the bottom VS Code taskbar..

## First steps
The Kaboom introduction is very beginner friendly.
https://kaboomjs.com/doc/intro

This tutorial will teach you how to:
- Load objects into your game (sprites)
- Implement movement for these objects
- Handle user input to control an object
- Create levels (scenes) for your game

## Exploring the programming patterns and possibilities
The demo games available in Kaboom Playground (e.g. https://kaboomjs.com/play?demo=rpg) are fantastic as case studies for the conventions and computational thinking patterns needed to develop games using Kaboom.

We highly recommend exploring these demos and their code (they are very beginner friendly while being very capable). You can easily extend and build on top of the excellent foundations provided to create a fully fledged game in the Playground browser.

### More fundamentals to explore
- Loops
- Collision 
- Layers (foreground, background, UI, like CSS z-index)
- Events
- Assets

### Additional resources
Walkthrough: Code Zelda in JavaScript with Kaboom.js!
https://www.youtube.com/watch?v=XX93O4ZVUZI
