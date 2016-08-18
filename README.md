# css-column-width 0.0.7

Css module of single purpose classes for column width

#### Stats

260 | 32 | 32
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev css-column-width
```

#### With Git

```
git clone https://github.com/tachyons-css/css-column-width
```

## Usage

#### Using with [PostCSS](https://github.com/postcss/postcss)

Import the css module

```css
@import "css-column-width";
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
<link rel="stylesheet" href="path/to/module/css/css-column-width">
```

#### Development

The source CSS files can be found in the `src` directory.
Running `$ npm start` will process the source CSS and place the built CSS in the `css` directory.

## The CSS

```css
/*
   COLUMN WIDTH
*/
.cw-auto { column-width: auto; }
.cw-xxs { column-width: 4rem; }
.cw-xs { column-width: 8rem; }
.cw-s { column-width: 16rem; }
.cw-m { column-width: 32rem; }
.cw-l { column-width: 48rem; }
.cw-xl { column-width: 64rem; }
.cw-i { column-width: inherit; }
@media screen and (min-width: 48em) {
 .cw-auto-ns { column-width: auto; }
 .cw-xxs-ns { column-width: 4rem; }
 .cw-xs-ns { column-width: 8rem; }
 .cw-s-ns { column-width: 16rem; }
 .cw-m-ns { column-width: 32rem; }
 .cw-l-ns { column-width: 48rem; }
 .cw-xl-ns { column-width: 64rem; }
 .cw-i-ns { column-width: inherit; }
}
@media screen and (min-width:48em) and (max-width: 64em) {
 .cw-auto-m { column-width: auto; }
 .cw-xxs-m { column-width: 4rem; }
 .cw-xs-m { column-width: 8rem; }
 .cw-s-m { column-width: 16rem; }
 .cw-m-m { column-width: 32rem; }
 .cw-l-m { column-width: 48rem; }
 .cw-xl-m { column-width: 64rem; }
 .cw-i-m { column-width: inherit; }
}
@media screen and (min-width: 64em) {
 .cw-auto-l { column-width: auto; }
 .cw-xxs-l { column-width: 4rem; }
 .cw-xs-l { column-width: 8rem; }
 .cw-s-l { column-width: 16rem; }
 .cw-m-l { column-width: 32rem; }
 .cw-l-l { column-width: 48rem; }
 .cw-xl-l { column-width: 64rem; }
 .cw-i-l { column-width: inherit; }
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
