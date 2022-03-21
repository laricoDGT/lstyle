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

to removes any unused CSS for best performance use `postcss-purgecss` and `postcss-import`.

example of `postcss.config.js` file.

```js
const purgecss = [
  '@fullhuman/postcss-purgecss',
  {
    content: ['./components/**/*.js', './pages/**/*.js'],
    defaultExtractor: (content) => content.match(/[\w-/:]+(?<!:)/g) || [],
  },
]

module.exports = {
  plugins: ['postcss-import', ...(process.env.NODE_ENV === 'production' ? [purgecss] : [])],
}
```

Or Use CDN

```bash
https://lstyle.larico.net/dist/lstyle.min.css

```

<!-- See [options](config.md). -->
