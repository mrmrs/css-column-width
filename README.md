# CSS COLUMN WIDTH

  Mobile-first classes for css-column-width.
  Set the desired css-column-width on any element for any breakpoint.
  Base class names are namespaced across three breakpoints:

*  -ns = not-small (covers everything larger than mobile)
*  -m  = medium
*  -l  = large

## Install
Grab the css partial from github and include it in your project or alternatively
you can install it via npm:
```
npm install --save-dev css-column-width
```
View on [npm](https://www.npmjs.org/package/css-column-width)


## File Size

1.4K column-width.css
1.0K column-width.min.css

## The Code
```
.cw-auto {    column-width: auto; }
.cw-xxs {     column-width: 4rem; }
.cw-xs {      column-width: 8rem; }
.cw-s {       column-width: 16rem; }
.cw-m {       column-width: 32rem; }
.cw-l {       column-width: 48rem; }
.cw-xl {      column-width: 64rem; }
.cw-i {       column-width: inherit; }

@media screen and (min-width: 48em) {
  .cw-auto-ns {    column-width: auto; }
  .cw-xxs-ns {     column-width: 4rem; }
  .cw-xs-ns {      column-width: 8rem; }
  .cw-s-ns {       column-width: 16rem; }
  .cw-m-ns {       column-width: 32rem; }
  .cw-l-ns {       column-width: 48rem; }
  .cw-xl-ns {      column-width: 64rem; }
  .cw-i-ns {       column-width: inherit; }
}

@media screen and (min-width: 48em) and (max-width: 64em) {
  .cw-auto-m {    column-width: auto; }
  .cw-xxs-m {     column-width: 4rem; }
  .cw-xs-m {      column-width: 8rem; }
  .cw-s-m {       column-width: 16rem; }
  .cw-m-m {       column-width: 32rem; }
  .cw-l-m {       column-width: 48rem; }
  .cw-xl-m {      column-width: 64rem; }
  .cw-i-m {       column-width: inherit; }
}

@media screen and (min-width: 64em)  {
  .cw-auto-l {    column-width: auto; }
  .cw-xxs-l {     column-width: 4rem; }
  .cw-xs-l {      column-width: 8rem; }
  .cw-s-l {       column-width: 16rem; }
  .cw-m-l {       column-width: 32rem; }
  .cw-l-l {       column-width: 48rem; }
  .cw-xl-l {      column-width: 64rem; }
  .cw-i-l {       column-width: inherit; }
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

