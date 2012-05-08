dynamicgif.less
===============

Dynamic GIF generation in Less.

This is a module for the LESS CSS preprocessor (http://lesscss.org/).
It allows you generate GIF images as data-URIs dynamically.

For more information on how this works and why you would want to do this
in the first place, see http://micheljansen.org/blog/entry/1238


Usage
-----

The following three classes each have dynamically background-image:

>     @import "dynamicgif.less";
>
>     .red {
>         .gifhex(#ff0000);
>     }
>
>     .green {
>         .gifhex(#00FF00);
>     }
>
>     .blue {
>         .gifrgb(0,0,255);
>     }


License
-------

Dynamicgif.less is licensed under MIT license. Do whatever you want with
it :)

Copyright (C) 2012 Michel Jansen

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
