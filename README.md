# Sailor

Meet Sailor, a vanilla `.js` standalone, Wordpress pages transitions loader, condensed in a 1.6 kilobytes, one-line of code.

## Installation

As simple as adding the following lines to the top of your Wordpress `function.php` file.

```
add_action( 'wp_loaded', function() {
  wp_enqueue_script( 'sailor_js', get_template_directory_uri() . '/sailor.min.js', array(), '1.0.0', true );
}, PHP_INT_MAX );
```
## Theme

To change the theme color, edit the `theme` variable with the new color code.

```
var theme="#2774ab", // ...
```



