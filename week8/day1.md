## DOM Manipulation with D3

* [Interactive Data Visualization for the Web](http://chimera.labs.oreilly.com/books/1230000000345)
  * [Chapter 1](http://chimera.labs.oreilly.com/books/1230000000345/ch01.html)
  * [Chapter 2](http://chimera.labs.oreilly.com/books/1230000000345/ch02.html)
  * [Chapter 3](http://chimera.labs.oreilly.com/books/1230000000345/ch03.html)

1. Complete the [Javascript Warmup](javascript-warmup.md)
2. Create a rectangle of `width` 960px and `height` 500px composed of 5000 `orange` and `grey` circles.  For extra credit implement [collision detection](http://bl.ocks.org/mbostock/3231298) on the particles.

  ![](https://gist.githubusercontent.com/Jay-Oh-eN/b84846a0511acfeaf925/raw/dc33b828def4f724168874ab9408e4a78a050200/thumbnail.png)
  
3. Adapt the code for your to color each circle to create an orange circle or radius 150px centered at the middle of the canvas.

  > For reference the equation of a circle centered at (h, k) is: (x - h)^2 + (y - k) ^ 2 = r^2 

  ![](https://gist.githubusercontent.com/Jay-Oh-eN/e17eafaab5e094f55e71/raw/7902716dcf93be2855aef998a6d9a18c2dd50d92/thumbnail.png)

You should use [blockbuilder.org](http://blockbuilder.org) and the following Javascript and `d3` functions:

* Javascript [`for` loop](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Loops_and_iteration)
* [`Math.random()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/random)
* [`Math.pow()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/pow)
* [`d3.select()`](https://github.com/mbostock/d3/wiki/Selections#d3_select)
* [`d3.append()`](https://github.com/mbostock/d3/wiki/Selections#append)
* [`d3.attr()`](https://github.com/mbostock/d3/wiki/Selections#attr)
* [`d3.style()`](https://github.com/mbostock/d3/wiki/Selections#style)
* [`d3.datum()`](https://github.com/mbostock/d3/wiki/Selections#datum)