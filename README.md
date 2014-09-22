# CSS TEXT OVERFLOW

  Mobile-first classes for css-text-overflow.
  Set the desired css-text-overflow on any element for any breakpoint.
  Base class names are namespaced across three breakpoints:

*  -ns = not-small (covers everything larger than mobile)
*  -m  = medium
*  -l  = large

## Install
Grab the css partial from github and include it in your project or alternatively
you can install it via npm:
```
npm install --save-dev css-text-overflow
```
View on [npm](https://www.npmjs.org/package/css-text-overflow)


## File Size

1.3K text-overflow.css
968B text-overflow.min.css 
226B minified and gzipped

## The Code
```
.t-clip { text-overflow: clip; }
.t-ellipsis { text-overflow: ellipsis; }
.t-dots { text-overflow: "…"; }

/* Two-value syntax: the first value describes the overflow at the left end of the line,
                     the second at the right end. Directionality has no influence */

.t-clip-ellipsis { text-overflow: clip ellipsis; }
.t-double { text-overflow: "…" "…"; }
.t-i { text-overflow: inherit; }

@media screen and (min-width: 48em) {
  .t-clip-ns { text-overflow: clip; }
  .t-ellipsis-ns { text-overflow: ellipsis; }
  .t-dots-ns { text-overflow: "…"; }
  .t-clip-ellipsis-ns { text-overflow: clip ellipsis; }
  .t-double-ns { text-overflow: "…" "…"; }
  .t-i-ns { text-overflow: inherit; }
}

@media screen and (min-width: 48em) and (max-width: 64em) {
  .t-clip-m { text-overflow: clip; }
  .t-ellipsis-m { text-overflow: ellipsis; }
  .t-dots-m { text-overflow: "…"; }
  .t-clip-ellipsis-m { text-overflow: clip ellipsis; }
  .t-double-m { text-overflow: "…" "…"; }
  .t-i-m { text-overflow: inherit; }
}

@media screen and (min-width: 64em)  {
  .t-clip-l { text-overflow: clip; }
  .t-ellipsis-l { text-overflow: ellipsis; }
  .t-dots-l { text-overflow: "…"; }
  .t-clip-ellipsis-l { text-overflow: clip ellipsis; }
  .t-double-l { text-overflow: "…" "…"; }
  .t-i-l { text-overflow: inherit; }
}

```

## Author

[http://mrmrs.cc - Entire internet gateway to all things mrmrs](http://mrmrs.cc)
[http://mrmrs.io - Open source projects](http://mrmrs.io)

## License

The MIT License (MIT)

Copyright (c) 2014 @mrmrs

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

