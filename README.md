# Simptip [v1.0.4]
####A simple CSS tooltip made with Sass

###[Visit Site, Documentation and some examples](http://arashm.net/lab/simptip/)


###Installation

I'll explain with an example:
```html
<link rel="stylesheet" type="text/css" href="simptip-mini.css" />
```
or:
```html
<link rel="stylesheet" type="text/css" href="simptip.css" />
```

###Usage

Then you can do something like this:
```html
<span class="simptip-position-top" data-tooltip="Tooltip's content"> Text </span>
```
What you see in the data-tooltip attribute is the text content of the tooltips, and the value of class attribute is tooltop's position.

You can use `.simptip-position-right` , `.simptip-position-bottom` and `.simptip-position-left` class for other positions that you would like.

You can also use more features of Simptip by adding these classes:
- `.half-arrow` : change tooltip's arrow to half arrow
- `.simptip-smooth` : makes soft edge for tooltip
- `.simptip-fade` : fades effect for show/hide
- `.simptip-movable` : shows movable effect
- `.simptip-multiline` : makes multiline body for tooltip
- `.simptip-success` : changes color to green spectrum
- `.simptip-info` : changes color to blue spectrum
- `.simptip-warning` : changes color to orange spectrum
- `.simptip-danger` : changes color to red spectrum

######[Let me know if you use it in your projects.](https://twitter.com/arashmanteghi)

###License
Copyright (c) 2013 Arash Manteghi

Licensed under the [MIT license](http://opensource.org/licenses/MIT).
