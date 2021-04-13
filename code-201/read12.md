'[HOME](../README.md)'<br/>

## Docs for the HTML <canvas> Element & Chart.js

* CHARTS:
    * easy to look at and convey data
    * `chart.js` is a javascript plugin that uses html `<canvas>` element to draw graphs.

* CANVAS TAG:
    * it it similer to `<img>` tag, but is has just two attributes `width` and `hight`. 
    * we can specify a **fallback** content to `<canvas>` tag in case of browsers versions issues.
    * require the closing tag.
    * there are a **2d** redering context.
    * the canvace is initially blanck, we use `getContext()`, which a method in canvas element, to draw some thing.

* DRAWING SHAPES WITH CANVAS:
    * grid
    * rectangle
        * `fillRect(x, y, width, height)`
        * `strokeRect(x, y, width, height)`
        * `clearRect(x, y, width, height)`
    * drawing pathes
        * `beginPath()`
        * `closePath()`
        * `stroke()`
        * `fill()`
    * drawing a triangle
    * moving the pen
    * lines

* APPLYING STYLES AND COLORS:
    * `fillStyle = color`
    * `strokeStyle = color`
    * line styles