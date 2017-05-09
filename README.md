
# of-webpack-zepto

Zepto for npm.

自定义构建模块 MODULES="zepto event form data assets selector touch" npm run-script dist


##Install

`npm install of-webpack-zepto --save`

##Usage -- webpack

`import $ from 'of-webpack-zepto'`

`new webpack.ProvidePlugin({
  $: 'jquery'
}) // 自动加载模块`

##Links

http://zeptojs.com/

https://www.npmjs.com/package/of-webpack-zepto