
Two.js Browserify
------

A browserified two-dimensional drawing api meant for modern browsers.

This is a browserified package for [Two.js][official] .

[official]: http://jonobr1.github.io/two.js/

### Usage

```
npm install --save twojs-browserify
```
```coffee
Two = require 'twojs-browserify'
elem = document.querySelector '#container'

params = width: 200, height: 100
two = new Two(params).appendTo elem

circle = two.makeCircle 72, 70, 10
circle.fill = '#fff800'
circle.stroke = 'organered'
circle.linewidth = 5

two.update()
```

### Change Log

* `0.2.0`, wrap Two.js `0.2.0` into a NPM package

### License

MIT

For Two.js , see offical repo:

* https://github.com/jonobr1/two.js/blob/master/license.txt
* https://github.com/jonobr1/two.js/blob/master/package.json#L25