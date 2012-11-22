FuckYeah
========

FuckYeah is a jQuery plugin that adds awesomeness to any jQuery code.

## Getting Started
Download the [production version][min] or the [development version][max].

[min]: https://raw.github.com/artpolikarpov/fuckyeah/master/fuckyeah.jquery.min.js
[max]: https://raw.github.com/artpolikarpov/fuckyeah/master/fuckyeah.jquery.js

In your web page:

```html
<script src="jquery.js"></script>
<script src="fuckyeah.jquery.min.js"></script>
<script>
jQuery(function($) {
  $.fuckYeah();
});
</script>
```
## Examples
This is best jQuery plugin ever. Take a look:

```javascript
$(function () {
  // All you jQuery is now awesome
}).fuckYeah();
```

You can boost awesomeness and use <tt>fuckYeah()</tt> on every line if you like:

```javascript
$('#sexy').slideDown('slow').fuckYeah();

$('#sort-button').on('click', function () {
  sortState = !sortState;
  toggleSort();
}).fuckYeah();
```

Write your own aliases and get profit. But do not forget <tt>fuckYeah()</tt>:

```javascript
$.fn.noop = $.fn.fuckyeah;

var $more = $('.more');
$more[$more.is(':visible') ? 'fadeTo' : 'noop'](333, 0).fuckYeah();
```

jQuery (1.0+) is required.

## License
Copyright (c) 2012 Artem Polikarpov
Licensed under the MIT License.

### <br>
Looking forward for your pull requests with more live examples ;-)