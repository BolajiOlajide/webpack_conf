# Webpack Conf

Checking out this awesome [webpack tutorial](https://www.valentinog.com/blog/webpack-tutorial/)

If you don't want to use a `.babelrc` and need to specify webpack loaders you can use `module-bind`

```json
"scripts": {
    "dev": "webpack --mode development --module-bind js=babel-loader",
    "build": "webpack --mode production --module-bind js=babel-loader"
}
```
