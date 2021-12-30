# Vanilla-JS-Pages-Transition-Loader

A simple and minimalistic vanilla `.js` standalone pages transition loader, minified in a 1.1 kilobytes, one-line of code.

## Fundamentals

- Generate a `<script>` element appended to the `<head>` element, containing any required styling.
- Generate a `<div>` element, with the identifier `id="o"` acting as overlay, prepended to the `<body>` element.
- Generate a `<svg>` element, acting as loader, prepended to the previously generated `<div>` element.
- On `window.onload` self generated elements are automatically removed.

## Demo

||||
|-|-|-|
|<img src="https://i.ibb.co/L68sYxD/Vanilla-js-pages-transitions-loader-ressource-1.gif"></img>|<img src="https://i.ibb.co/ZH4PXWZ/vanilla-js-pages-transitions-loader-ressource-2.gif"></img>|<img src="https://i.ibb.co/J7y9BYy/vanilla-js-pages-transitions-loader-ressource-3.gif"></img>|

See it live @ https://codepen.io/amarinediary/full/mdrQvGJ.

## Quick start

to enable it, place the following script near the end of your pages, right before the closing `</body>` tag.

```html
<script type="application/javascript" src="../path/to/vanilla-js-pages-transition-loader.min.js"></script>
```

## Theme

To change the theme's color, edit the theme's ` t ` variable with your new HEX color code located at the top of the script.

```js
var t="#2774ab", // ...
```

The default theme's color is based on Wordpress deep blue accent ![#2774ab](https://via.placeholder.com/15/2774ab/000000?text=+) `#2774ab`.

## Time on screen

The time on screen is appended to the page loading time. To increase the time on screen you can modify the default `100` milliseconds `setTimeout` value located at the end of the script.
```js
// ...
,100)})
```

### Star it and watch it! 

We made your day? Give us a star!

