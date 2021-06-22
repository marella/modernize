# [modernize](https://github.com/marella/modernize/blob/main/modernize.css)

`normalize.css` with useful defaults for modern browsers.

## Installation

```sh
npm install modernize
```

## Usage

Import in HTML:

```html
<link href="https://cdn.jsdelivr.net/npm/modernize" rel="stylesheet">
```

#### Webpack

Import in JS:

```js
import 'modernize';
```

or import in CSS or Sass:

```css
@import 'modernize';
```

## What does it do?

- Normalizes styles for a wide range of elements
- Corrects bugs and common browser inconsistencies
- Provides common, useful defaults
- Explains what code does using detailed comments

## Browser support

- Chrome (latest)
- Edge (latest)
- Firefox (latest)
- Opera (latest)
- Safari (latest)

## Differences from `normalize.css`

- Includes latest styles from [`csstools/normalize.css`](https://github.com/csstools/normalize.css/blob/11.0.1/normalize.css)
- Includes and marks opinionated styles from [`necolas/normalize.css`](https://github.com/necolas/normalize.css/blob/8.0.1/normalize.css)
- Adds useful defaults such as `box-sizing: border-box`
- Uses system fonts
- Drops support for Internet Explorer
