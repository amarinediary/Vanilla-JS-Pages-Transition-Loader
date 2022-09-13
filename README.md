# Vanilla JS Pages Transition Loader

A simple and minimalistic, VanillaJS, standalone, pages transition loader, minified in a `1.31` kilobytes, one-line of code.

## Fundamentals

- Generate a `<script>` element appended to the `<head>` element, containing any required styling.
- Generate a `<div>` element, acting as overlay, prepended to the `<body>` element.
- Generate a `<svg>` element, acting as loader, prepended to the previously generated `<div>` element.
- On `window.onload` self generated elements are automatically removed.

## [Demo](https://codepen.io/amarinediary/full/mdrQvGJ)

||||
|-|-|-|
|<img src="https://i.ibb.co/L68sYxD/Vanilla-js-pages-transitions-loader-ressource-1.gif"></img>|<img src="https://i.ibb.co/ZH4PXWZ/vanilla-js-pages-transitions-loader-ressource-2.gif"></img>|<img src="https://i.ibb.co/J7y9BYy/vanilla-js-pages-transitions-loader-ressource-3.gif"></img>|

## Quick start

to enable it, place the following script near the end of your pages, right before the closing `</body>` tag.

```html
<script type="application/javascript" src="../path/to/vanilla-js-pages-transition-loader.min.js"></script>
```

## Settings

```js
let settings = {
    backgroundColor: "#2774ab",
    filterBrightness: 2,
    strokeWidth: 10,
    timeOnScreen: 100
}, //...
```

|Option|Description|
|-|-|
|`backgroundColor`|Refer to [MDN Web Docs color](https://developer.mozilla.org/en-US/docs/Web/CSS/color_value) for acceptable values. The [background-color CSS property](https://developer.mozilla.org/en-US/docs/Web/CSS/background-color) sets the background color of an element. Default to Wordpress deep blue accent ![#2774ab](https://via.placeholder.com/15/2774ab/000000?text=+) `#2774ab`|
|`filterBrightness`| [number](https://developer.mozilla.org/en-US/docs/Web/CSS/number) or [percentage](https://developer.mozilla.org/en-US/docs/Web/CSS/percentage). The brightness of the `svg` loader element ([brightness() CSS function](https://developer.mozilla.org/en-US/docs/Web/CSS/filter-function/brightness())). A value under `100%` darkens the loader, while a value over `100%` brightens it. The lacuna value for interpolation is `1`. Default to `2`.|
|`strokeWidth`|Positive `integer`. Loader stroke's width. The [stroke-width](https://developer.mozilla.org/en-US/docs/Web/SVG/Attribute/stroke-width) attribute is a presentation attribute defining the width of the stroke to be applied to the shape. Default to `10`.|
|`timeOnScreen`|Positive `integer`. The time on screen is appended to the page loading time. Default to `100` milliseconds.|

## Watch it, Star it, Fork it ! 

We made your day? Give us a star!

