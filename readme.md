# Scroll on hover website image example

![Hover Effect Example](https://github.com/iamjmitch/scrolling-website-example/blob/master/example.gif?raw=true)

Vanilla JS script test to emulate scrolling a website when hovering over a picture

**_background-color_** can be set via the CSS and is not hardcoded into the image.

**_mobile responsive_**. some minor positioning tweaks may be needed if scaling alot higher than demo width.

**_onmouseover_** runs a script to calculate the difference in pixel height between the scrolling image and the div window emulating the laptop screen. That pixel difference is then used to adjust the margin of the scrolling image to emulate the effect of a scrolling website.

**_onmouseout_** runs a script to return the scrolling image to its original position. Also speeds up the transition CSS property from 0.7s to 0.1s for better user experience.

**_see example_** [Here.](https://codepen.io/iamjmitch/pen/zYBWoLY)

