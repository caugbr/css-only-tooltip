# CSS-only tooltip

A simple tooltip made in pure CSS. Just put the ```data-tooltip-text``` attribute in any HTML tag. Use the classes ```top```, ```right```, ```bottom``` and ```left``` to define the position of the tooltip and ```fade``` to apply a fade effect to the tooltip.

### How to use it:

HEAD
```html
<link rel="stylesheet" type="text/css" href="css-only-tooltip.css">
```

BODY
```html
<span class="fade right" data-tooltip-text="This tooltip appears on the right, with a fade effect">Element with tooltip</a>