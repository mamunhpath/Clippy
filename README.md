[Clippy](http://bennettfeely.com/clippy)
======

Shape up your website with CSS clip-paths.

Clippy is a tool for generating values for shape functions with the CSS clip-path property. The property accepts several basic shapes that will be able to create with Clippy:

* `circle()` 
* `ellipse()`
* `rect()`
* `polygon()`
* `inset()`

This is really my project I've worked on with Github...



#### Details
* Utilizes [dragabilly.js](https://github.com/desandro/draggabilly) for the handles which each correspond to a point for CSS clip path. Works really well on touch devices, especially with the `touch-action` property.
* Using Grunt with SCSS, autoprefixer, minification for CSS, HTML, and soon, jQuery and images.
* Material design-ish inspiration.
* Mobile-first design, making things work great on mobile touch devices and will work responsively upwards from there.


#### To do

* Get `circle()` working better when the demo area is not a 1:1 ratio.
* Start working on  `ellipse()` with much reused from `circle()`, but more complex.
* Make a favicon.
* Make a panel card with quick information about the `clip-path` property.
* Look up browser support and create a panel card with that information.
* Get cooler images?

