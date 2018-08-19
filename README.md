# Web Fractals

This is an initial stab at converting my Java fractal generator into Javascript.   Well, not all 6000 lines of it!
Delighted that, after only one minor syntax error in my js, my initial attempt at generating a Mandelbrot set actually produced one, albeit in lurid tones and only two of them at that, rather than the 256 shades I was expecting.   OK, some more work needed!

So, now refactored code to get rid of hard-coded width and height, though at this stage setting as consts and my HTML canvas-wrapper has a fixed size at present.   Mainly it just meant changing the pixelToComplex() function and the draw() function.

Got rid of canvas wrapper and just put an id on the canvas.   Need to minimize extra pixels creeping in!

Mostly sorted the geometry of zooming (stole code from my own Java program FracGenWX!).

The two main things now are 
1. for me to understand how mouse events propagate and are or are not consumed, and
2. tp improve the colour mapping

