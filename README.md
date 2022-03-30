# gridsome-facebook-pixel

> Simply integrate Facebook Pixel with Gridsome

## Installation

`yarn add gridsome-plugin-facebook-pixel`

## Usage

`gridsome.config.js`

```js
module.exports = {
  plugins: [
    'gridsome-plugin-facebook-pixel'
  ]
}
```

## Configuration

The default config options will take `pixelId`.

```js
{
  use: 'gridsome-plugin-facebook-pixel',
  options: {
    pixelId: '123456789'
  }
}
```
