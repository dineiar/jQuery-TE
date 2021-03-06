﻿What is jQuery TE?
 ==================

jQuery TE is a jQuery plugin. It is a lightweight and very useful HTML editor. And it works with WYSIWYG model.

Most importantly, it can be integrated into your system in 1 minute. And you can modify it as you want in terms of interface. Even you can change the css classes.

Everything is as simple as the following:  
`$("textarea").jqte();`

Cross Browser
-------------
jQuery TE works with same performance on the most preferred browsers. And its source of the output is same as 90% on these browsers.

Also, it compresses to source of the output automatically. jQuery TE's system runs more practical and more rapidly to other some editors.

We recommend that you use this product with the latest version of jQuery.

[Demo page][]

[Download page][]

[Documentation page][]

[Comments page][]

  [Demo page]: http://jqueryte.com/demos
  [Download page]: http://jqueryte.com/download
  [Documentation page]: http://jqueryte.com/documentation
  [Comments page]: http://jqueryte.com/comments

If you have created a textarea and the value of class, such as “editor”
used with the **$(“.editor”).jqte();** will be enough to write script.

Of course you can also use a different attribute value.

Usage
-------------

First include the latest version of jQuery. Next, download and include jquery-te-1.4.1.min.js and jquery-te-1.4.1.css (inside to head tags)

``` html
<script type="text/javascript" src="http://code.jquery.com/jquery.min.js"></script>
<script type="text/javascript" src="jquery-te-1.4.1.min.js"></script>
<link type="text/css" rel="stylesheet" href="jquery-te-1.4.1.css" charset="utf-8" />
```

After than, create a textarea inside to body tags

``` html
<textarea></textarea>
```

Finally, run this plugin
``` html
<script>
	$("textarea").jqte();
</script>
```

That's it!

Differences from the original repo
-------------

As this project seems not to be maintained by the original author anymore, I forked it to publish some changes/improvements that I made to it to fit my needs.

1. Nov 22 2015 - Added version 1.4.0 from the [original author's website](http://jqueryte.com/download)
2. Mar 01 2016 - Released version 1.4.1

Changelog
-------------

Version 1.4.1
- implementation of "variables"
- adjustments on IE compatibility
- added namespace on button click events
- clicking on the link button when the link area is visible hides it
- minor bugfixes


