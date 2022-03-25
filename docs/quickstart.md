# Let's Gget It Started

## 1. Install

```bash
yarn add lstyle
```

or

```bash
npm i lstyle
```

## 2. import lstyle

Import lstyle in your base layout

```
import "lstyle/dist/lstyle.css"
```

### Performance

to removes any unused CSS for best performance use `postcss-purgecss`

example of `postcss.config.js` file.

```js
const purgecss = require('@fullhuman/postcss-purgecss')

module.exports = {
  plugins: [
    purgecss({
      content: ['./**/*.html'],
    }),
  ],
}
```

Or Use CDN

```bash
https://lstyle.larico.net/dist/lstyle.min.css

```

<!-- See [options](config.md). -->
