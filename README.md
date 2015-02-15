# FastBlur.js - Fast blur

Superfast Blur - A pretty fast box blur for Canvas by Mario Klingemann, Quasimondo.

  * **More informations:** http://incubator.quasimondo.com/processing/superfast_blur.php
  * **Demo:** http://www.quasimondo.com/BoxBlurForCanvas/FastBlurDemo.html

Original source:

  * http://www.quasimondo.com/BoxBlurForCanvas/FastBlur.js


## Usage

**Image as source:**

```javascript
boxBlurImage(sourceImageID, targetCanvas, radius, blurAlphaChannel);
```

**RGBA Canvas as source:**

```javascript
boxBlurCanvasRGBA(targetContext, top_x, top_y, width, height, radius);
```

  * `targetContext`: the `CanvasRenderingContext2D`.

**RGB Canvas as source:**

```javascript
boxBlurCanvasRGB(targetContext, top_x, top_y, width, height, radius);
```

  * `targetContext`: the `CanvasRenderingContext2D`.


## Copying

```
Copyright (c) 2011 Mario Klingemann

Permission is hereby granted, free of charge, to any person
obtaining a copy of this software and associated documentation
files (the "Software"), to deal in the Software without
restriction, including without limitation the rights to use,
copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the
Software is furnished to do so, subject to the following
conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES
OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT
HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY,
WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING
FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR
OTHER DEALINGS IN THE SOFTWARE.
```
