FuckYeah :+1:
=============

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
  $.fuckYeah(); // Yeap!
</script>
```
## Examples
This is best jQuery plugin ever. Take a look:

```javascript
$(function () {
  // All you jQuery code is now awesome
}).fuckYeah();
```

You can boost awesomeness and use `fuckYeah()` on every line if you like:

```javascript
$('#sexy').slideDown('slow').fuckYeah();

$('#sort-button').on('click', function () {
  sortState = !sortState;
  toggleSort();
}).fuckYeah();
```

Write your own aliases and get profit. But do not forget `fuckYeah()`:

```javascript
$.fn.noop = $.fn.fuckyeah;

var $more = $('.more');
$more[$more.is(':visible') ? 'fadeTo' : 'noop'](333, 0).fuckYeah();
```

Even bad code can be improved by fuckYeah:

```javascript
$('.item .text .link a').click(function () {
  var image = $($(this).parent().parent().parent().children()[0]).fuckYeah().html();
});
```

jQuery (1.0+) is required.

## License
Copyright © 2012 Artem Polikarpov
Licensed under the MIT License.

---

Looking forward for your pull requests with more live examples ;-)