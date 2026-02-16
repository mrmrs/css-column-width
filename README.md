# css-column-width

Functional CSS for column-width

## Filesize

| File | Size |
|------|------|
| `dist/column-width.css` | 1417 bytes |
| `dist/column-width.min.css` | 971 bytes (212 Gzipped) |

## Install

```sh
npm install css-column-width
```

## Usage

### Import

```css
@import "css-column-width";
```

### CDN

```html
<link rel="stylesheet" href="https://unpkg.com/css-column-width/dist/column-width.min.css">
```

### Direct

```html
<link rel="stylesheet" href="path/to/css-column-width/dist/column-width.min.css">
```

## Classes

| Class   | Value                    |
|---------|--------------------------|
| `.cw-auto` | `column-width: auto;` |
| `.cw-xxs` | `column-width: 4rem;` |
| `.cw-xs` | `column-width: 8rem;` |
| `.cw-s` | `column-width: 16rem;` |
| `.cw-m` | `column-width: 32rem;` |
| `.cw-l` | `column-width: 48rem;` |
| `.cw-xl` | `column-width: 64rem;` |
| `.cw-i` | `column-width: inherit;` |
| `.cw-auto-s` | `column-width: auto;` |
| `.cw-xxs-s` | `column-width: 4rem;` |
| `.cw-xs-s` | `column-width: 8rem;` |
| `.cw-s-s` | `column-width: 16rem;` |
| `.cw-m-s` | `column-width: 32rem;` |
| `.cw-l-s` | `column-width: 48rem;` |
| `.cw-xl-s` | `column-width: 64rem;` |
| `.cw-i-s` | `column-width: inherit;` |
| `.cw-auto-m` | `column-width: auto;` |
| `.cw-xxs-m` | `column-width: 4rem;` |
| `.cw-xs-m` | `column-width: 8rem;` |
| `.cw-s-m` | `column-width: 16rem;` |
| `.cw-m-m` | `column-width: 32rem;` |
| `.cw-l-m` | `column-width: 48rem;` |
| `.cw-xl-m` | `column-width: 64rem;` |
| `.cw-i-m` | `column-width: inherit;` |
| `.cw-auto-l` | `column-width: auto;` |
| `.cw-xxs-l` | `column-width: 4rem;` |
| `.cw-xs-l` | `column-width: 8rem;` |
| `.cw-s-l` | `column-width: 16rem;` |
| `.cw-m-l` | `column-width: 32rem;` |
| `.cw-l-l` | `column-width: 48rem;` |
| `.cw-xl-l` | `column-width: 64rem;` |
| `.cw-i-l` | `column-width: inherit;` |

### Responsive

Responsive variants are available for each class with the following suffixes:

| Suffix | Media Query              |
|--------|--------------------------|
| `-s`   | `min-width: 32em`        |
| `-m`   | `min-width: 48em`        |
| `-l`   | `min-width: 96em`        |

Example: `.cw-auto-m` applies the property at the medium breakpoint and above.

## Building

```sh
npm run build
```

Processes `src/column-width.css` with [Lightning CSS](https://lightningcss.dev) and outputs to `dist/`.

- `dist/column-width.css` — formatted
- `dist/column-width.min.css` — minified

## License

MIT
