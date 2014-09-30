Responsive-Sticky-Footer
========================

A simple hack to make a responsive sticky footer

## HTML
```html
<!doctype html>
<html>
    <head>
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1">
        <title>Full-Screen Background Slider</title>
    </head>
    <body>
      <header></header>
      <section></section>
      <footer></footer>
    </body>
</html>

```

### [Sass](http://sass-lang.com/) + [Bourbon](http://bourbon.io/)
```sass
body 
	display: table
	+size(100%)
	
header, footer
	height: 1px
	
header 
	display: table-header-group

footer 
	display: table-footer-group
```

## Licensing

This code snippet is licensed under a [BY-SA Creative Commons License](http://creativecommons.org/licenses/by-sa/3.0/). You have the freedom to copy, adapt, and transmit this resource in any manner you see fit.
