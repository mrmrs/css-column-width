# css-column-width 1.0.6

Css module of single purpose classes for column width

#### Stats

336 | 32 | 96
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev css-column-width
```

Learn more about using css installed with npm:
* https://webpack.github.io/docs/stylesheets.html
* https://github.com/defunctzombie/npm-css

#### With Git

http:
```
git clone https://github.com/tachyons-css/css-column-width
```

ssh:
```
git clone git@github.com:tachyons-css/css-column-width.git
```

## Usage

#### Using with [Postcss](https://github.com/postcss/postcss)

Import the css module

```css
@import "css-column-width";
```

Then process the css using the [`tachyons-cli`](https://github.com/tachyons-css/tachyons-cli)

```sh
$ npm i -g tachyons-cli
$ tachyons path/to/css-file.css > dist/t.css
```

#### Using the css

##### CDN
The easiest and most simple way to use the css is to use the cdn hosted version. Include it in the head of your html with:

```
<link rel="stylesheet" href="http://unpkg.com/css-column-width@1.0.6/css/css-column-width.min.css" />
```

##### Locally
The built css is located in the `css` directory. It contains an unminified and minified version.
You can either cut and paste that css or link to it directly in your html.

```html
<link rel="stylesheet" href="path/to/module/css/css-column-width">
```

#### Development

The source css files can be found in the `src` directory.
Running `$ npm start` will process the source css and place the built css in the `css` directory.

## The css

```css
/*
   COLUMN WIDTH
*/
.cw-auto { -webkit-column-width: auto; -moz-column-width: auto; column-width: auto; }
.cw-xxs { -webkit-column-width: 4rem; -moz-column-width: 4rem; column-width: 4rem; }
.cw-xs { -webkit-column-width: 8rem; -moz-column-width: 8rem; column-width: 8rem; }
.cw-s { -webkit-column-width: 16rem; -moz-column-width: 16rem; column-width: 16rem; }
.cw-m { -webkit-column-width: 32rem; -moz-column-width: 32rem; column-width: 32rem; }
.cw-l { -webkit-column-width: 48rem; -moz-column-width: 48rem; column-width: 48rem; }
.cw-xl { -webkit-column-width: 64rem; -moz-column-width: 64rem; column-width: 64rem; }
.cw-i { -webkit-column-width: inherit; -moz-column-width: inherit; column-width: inherit; }
@media screen and (min-width: 48em) {
 .cw-auto-ns { -webkit-column-width: auto; -moz-column-width: auto; column-width: auto; }
 .cw-xxs-ns { -webkit-column-width: 4rem; -moz-column-width: 4rem; column-width: 4rem; }
 .cw-xs-ns { -webkit-column-width: 8rem; -moz-column-width: 8rem; column-width: 8rem; }
 .cw-s-ns { -webkit-column-width: 16rem; -moz-column-width: 16rem; column-width: 16rem; }
 .cw-m-ns { -webkit-column-width: 32rem; -moz-column-width: 32rem; column-width: 32rem; }
 .cw-l-ns { -webkit-column-width: 48rem; -moz-column-width: 48rem; column-width: 48rem; }
 .cw-xl-ns { -webkit-column-width: 64rem; -moz-column-width: 64rem; column-width: 64rem; }
 .cw-i-ns { -webkit-column-width: inherit; -moz-column-width: inherit; column-width: inherit; }
}
@media screen and (min-width:48em) and (max-width: 64em) {
 .cw-auto-m { -webkit-column-width: auto; -moz-column-width: auto; column-width: auto; }
 .cw-xxs-m { -webkit-column-width: 4rem; -moz-column-width: 4rem; column-width: 4rem; }
 .cw-xs-m { -webkit-column-width: 8rem; -moz-column-width: 8rem; column-width: 8rem; }
 .cw-s-m { -webkit-column-width: 16rem; -moz-column-width: 16rem; column-width: 16rem; }
 .cw-m-m { -webkit-column-width: 32rem; -moz-column-width: 32rem; column-width: 32rem; }
 .cw-l-m { -webkit-column-width: 48rem; -moz-column-width: 48rem; column-width: 48rem; }
 .cw-xl-m { -webkit-column-width: 64rem; -moz-column-width: 64rem; column-width: 64rem; }
 .cw-i-m { -webkit-column-width: inherit; -moz-column-width: inherit; column-width: inherit; }
}
@media screen and (min-width: 64em) {
 .cw-auto-l { -webkit-column-width: auto; -moz-column-width: auto; column-width: auto; }
 .cw-xxs-l { -webkit-column-width: 4rem; -moz-column-width: 4rem; column-width: 4rem; }
 .cw-xs-l { -webkit-column-width: 8rem; -moz-column-width: 8rem; column-width: 8rem; }
 .cw-s-l { -webkit-column-width: 16rem; -moz-column-width: 16rem; column-width: 16rem; }
 .cw-m-l { -webkit-column-width: 32rem; -moz-column-width: 32rem; column-width: 32rem; }
 .cw-l-l { -webkit-column-width: 48rem; -moz-column-width: 48rem; column-width: 48rem; }
 .cw-xl-l { -webkit-column-width: 64rem; -moz-column-width: 64rem; column-width: 64rem; }
 .cw-i-l { -webkit-column-width: inherit; -moz-column-width: inherit; column-width: inherit; }
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

