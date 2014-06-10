PDF417
======

Introduction
------

JavaScript PDF417 code generator.

Use the code
------

- `pdf417.js` (main library with _libbcmath_)
- `demo.js` (code array to canvas display demo script)

Usage
------

Insert `pdf417.js` first, then call `PDF417.init("some code here")`.

Calling `PDF417.getBarcodeArray()` will get a return object like:

```JSON
{
    num_rows: 120,
    num_cols: 226,
    bcode: [
        [
            0,
            0,
            1,
            1,
            1,
            0,
            ...
        ],
        [
            0,
            1,
            1,
            0,
            0,
            0,
            ...
        ],
        ...
    ]
}
```

Easy to draw a code using canvas.

Demo code is in `demo.js`.

[DEMO PAGE](http://jamesliu.info/pdf417)

License
------

The MIT License (MIT)

Copyright (c) 2014 James Liu <j@jamesliu.info>

Permission is hereby granted, free of charge, to any person obtaining a copy of
this software and associated documentation files (the "Software"), to deal in
the Software without restriction, including without limitation the rights to
use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of
the Software, and to permit persons to whom the Software is furnished to do so,
subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS
FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR
COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER
IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN
CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
