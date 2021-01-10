# Sailor

Meet Sailor, a vanilla `.js` standalone, Wordpress pages transitions loader, condensed in a 1.6 kilobytes, one-line of code.

## Installation

As simple as adding the following lines to the top of your Wordpress `function.php` file.

```php
add_action( 'wp_loaded', function() {
  wp_enqueue_script( 'sailor_js', get_template_directory_uri() . '/sailor.min.js', array(), '1.0.0', true );
}, PHP_INT_MAX );
```
## Theme

To change Sailor's theme color, edit the `theme` variable with the new color code.

```js
var theme="#2774ab", // ...
```

Sailor's default theme's colors is based on Wordpress deep blue accent colors ![#2774ab](https://via.placeholder.com/15/2774ab/000000?text=+) `#2774ab`.

