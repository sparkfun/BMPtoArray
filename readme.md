SparkFun Bitmap to Progmem Array
========================================

![SparkFun Micro OLED Breakout](https://cdn.sparkfun.com//assets/parts/1/2/6/6/6/Flexible-Grayscale-OLED-6.jpg)

[*SparkFun Flexible Grayscale Display (SPX-14543)*](https://www.sparkfun.com/products/14543)

This script takes in a bitmap and converts the bitmap into 4-bit grayscale. An array of bytes is generated that can be copy/pasted into a header file.

This is very useful if you have a bitmap that you'd like to output onto a grayscale display (like the SparkFun flexible OLED). I attempted to use the bitmap2lcd program but found it very hard to use and over blown (and costs money) to generate an image array.

Three bitmaps are provided as an example. Requires python v2.7.

Usage:

    python bmptoarray.py macaque.bmp
	(see output.txt for array)

You can find an example of how to implement the header file here: https://github.com/sparkfun/SparkFun_SSD1320_OLED_Arduino_Library/tree/master/examples/Example2_Graphics

This is pretty much my first hack at python so I greatly welcome improvements with a pull request.

License Information
-------------------

This product is _**open source**_!

The **code** is released under the GPL v3 license. See the included LICENSE.md for more information.

Distributed as-is; no warranty is given.

- Your friends at SparkFun.