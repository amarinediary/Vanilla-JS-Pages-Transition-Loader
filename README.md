# Sailor

Sailor, a Wordpress loader for your admin pages transitions.

## Installation

As simple as adding this line, to he top of your Wordpress `function.php` file.

```
<?php
add_action( 'admin_footer', 'sailor', PHP_INT_MIN );
function sailor() {
echo "<script type='text/javascript'>var theme='#2774ab',sailor=jQuery('<style media=\"screen\">@keyframes swell{to{transform:rotate(360deg)}}svg{animation:1s swell infinite linear}</style><aside id=\"sailor\"><svg height=\"50px\" width=\"50px\" style=\"filter:brightness(150%);\" preserveAspectRatio=\"xMidYMid\" viewBox=\"0 0 100 100\" xmlns=\"http://www.w3.org/2000/svg\"><circle cx=\"50\" cy=\"50\" r=\"35\" fill=\"none\" stroke=\"currentColor\" stroke-dasharray=\"164.93361431346415 56.97787143782138\" stroke-width=\"10\"></circle></svg></aside>').css({'background-color':theme,'color':theme,'display':'flex','align-items':'center','justify-content':'center','position':'fixed','top':0,'width':'100vw','height':'100vh','z-index':2147483647,}).appendTo('body');jQuery('*').css({'pointer-events':'none','user-select':'none','cursor':'wait',});jQuery(window).load(function(){sailor.fadeOut('fast',function(){jQuery('*').css({'pointer-events':'','user-select':'','cursor':'',});this.remove()})})</script>";
}; ?>
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.
