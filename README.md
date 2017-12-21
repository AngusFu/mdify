# md-vue-loader

## Install

```
$ npm install md-vue-loader --save-dev
```

## Use

```js
module: {
  rules: [
    test: /\.md$/,
    loader: [
    	{
        loader: 'md-vue-loader',
    	  options: {
          // render demo apps in Shadow DOM
          shadow: false,
          // `prism` or `highlight.js`
          highlight: 'prism'
    	  }
    	}
  	]
  ]
}
```

## Related

- [md2vue](https://github.com/AngusFu/md2vue/)
