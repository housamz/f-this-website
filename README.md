
# F This Website
An ~4KB game for your website.
![screenshot](images/screenshot.gif)
These space invaders are coming to F your website.
Every word they pass over will turn into a word of your choice until you shoot them.

Visit [my website](https://www.hmz.ie/) for a demo.

### How to Play
Use right and left arrow keys to move, and up arrow key to shoot.

### Installation
Add the files `f-this-website.min.js` and `f-this-website.min.css`to your HTML, and then you can start by clicking F2 on the keyboard.

### Settings
Call the class from your JavaScript as below
```js
new  FThisWebsite();
```

*Optional params:*
* container: The HTMl element where the game can change text. default: `document.body`
* word: The word you want to replace the page text when space invader passes over. default: `fudge`
* speed: The movement speed. default: `25`

Full example:
```js
new  FThisWebsite(document.body, " fudge ", 25);
```
