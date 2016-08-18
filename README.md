# css-text-overflow 0.0.6

Css module of single purpose classes for text overflow

#### Stats

357 | 24 | 24
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev css-text-overflow
```

#### With Git

```
git clone https://github.com/tachyons-css/css-text-overflow
```

## Usage

#### Using with [PostCSS](https://github.com/postcss/postcss)

Import the css module

```css
@import "css-text-overflow";
```

Then process the CSS using the [`tachyons-cli`](https://github.com/tachyons-css/tachyons-cli)

```sh
$ npm i -g tachyons-cli
$ tachyons-cli path/to/css-file.css > dist/t.css
```

#### Using the CSS

The built CSS is located in the `css` directory. It contains an unminified and minified version.
You can either cut and paste that css or link to it directly in your html.

```html
<link rel="stylesheet" href="path/to/module/css/css-text-overflow">
```

#### Development

The source CSS files can be found in the `src` directory.
Running `$ npm start` will process the source CSS and place the built CSS in the `css` directory.

## The CSS

```css
/*
   TEXT OVERFLOW
*/
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
@media screen and (min-width:48em) and (max-width: 64em) {
 .t-clip-m { text-overflow: clip; }
 .t-ellipsis-m { text-overflow: ellipsis; }
 .t-dots-m { text-overflow: "…"; }
 .t-clip-ellipsis-m { text-overflow: clip ellipsis; }
 .t-double-m { text-overflow: "…" "…"; }
 .t-i-m { text-overflow: inherit; }
}
@media screen and (min-width: 64em) {
 .t-clip-l { text-overflow: clip; }
 .t-ellipsis-l { text-overflow: ellipsis; }
 .t-dots-l { text-overflow: "…"; }
 .t-clip-ellipsis-l { text-overflow: clip ellipsis; }
 .t-double-l { text-overflow: "…" "…"; }
 .t-i-l { text-overflow: inherit; }
}
```

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

## Authors

* [mrmrs](http://mrmrs.io)
* [johno](http://johnotander.com)

## License

ISC
