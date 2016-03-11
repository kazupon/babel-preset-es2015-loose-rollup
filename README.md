# babel-preset-es2015-loose-rollup

babel-preset-es2015-loose for Rollup


# Installation

    $ npm install --save-dev babel-preset-es2015 babel-preset-es2015-loose
    $ npm install --save-dev https://github.com/kazupon/babel-preset-es2015-loose-rollup


## Usage

### `.babelrc` (Recommended)

**.babelrc**

```json
{
  "presets": ["es2015-loose-rollup"]
}
```

### babel-cli

    $ babel script.js --presets es2015-loose-rollup

### Node API

```javascript
require('babel-core').transform('code', {
  presets: ['es2015-minimal-rollup']
})
```


# License

## MIT

[MIT](http://opensource.org/licenses/MIT)
