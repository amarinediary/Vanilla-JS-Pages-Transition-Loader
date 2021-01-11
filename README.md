# Sailor

**Meet [Sailor][1]**, a vanilla `.js` standalone Wordpress pages transitions loader, condensed in a 1.3 kilobytes, one-line of code.

## Installation

As simple as adding the following lines to the top of your Wordpress `function.php` file & `sailor.min.js` to your root theme's directory.

```php
add_action( 'wp_loaded', function() {
  wp_enqueue_script( 'sailor_js', get_template_directory_uri() . '/sailor.min.js', array(), '1.0.0', true );
}, PHP_INT_MAX );
```
## Theme

To change Sailor's theme color, edit the theme ` t ` variable with the new color code.

```js
var t="#2774ab", // ...
```

Sailor's theme color is Wordpress deep blue accent color ![#2774ab](https://via.placeholder.com/15/2774ab/000000?text=+) `#2774ab`.

- We really love this neon pink ![#ec4188](https://via.placeholder.com/15/ec4188/000000?text=+) `#ec4188` with Sailor...
- Or this magnificent apple green ![#8db600](https://via.placeholder.com/15/8db600/000000?text=+) `#8db600`...
- Or even this deep dark blue-ish purple color ![#2a265f](https://via.placeholder.com/15/2a265f/000000?text=+) `#2a265f`.

[1]: https://github.com/amarinediary/Sailor/blob/main/README.md

