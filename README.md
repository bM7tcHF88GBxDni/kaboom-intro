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

## First steps
The Kaboom introduction is very beginner friendly and will explain the basics of creating sprites (essentially objects that you want in your game) and implementing their behaviour on user input.
https://kaboomjs.com/doc/intro
