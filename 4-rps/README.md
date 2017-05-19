# RPS
Rock, paper, scissors, shoot! We're going to encode the rules of the classic game into JavaScript. And for the first time, we're going to do so as a proper application. No more CodePen!

## File Structure
Check out what you have in this folder:

1. `index.html`
2. `app.js`
3. `style.css`

We know about the `index.html` and `style.css` files. The `app.js` is new, but we can probably figure out what's going on: this JavaScript will be linked to our HTML just like the CSS is. Except, instead of `<link>` tags, we're going to use a `<script>` tag.

### Why isn't it in `<head>`?
Because JS files can be huge, and we don't want to prevent the site from loading. Putting the `<script>` tag at the bottom of `<body>` lets us load JS last.

## Primary Objective
Using what you know about creating forms, JavaScript data types, and functions, make a playable Rock, Paper, Scissors game.

## Secondary Objective
Use CSS to make it look awesome.
