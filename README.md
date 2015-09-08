Promise Arrays [![NPM version][npm-version-image]][npm-url] [![Travis Build][travis-build-image]][travis-url] [![MIT License][license-image]][license-url]
===
[WIP] A super small library to help you map and filter arrays with async operations. The only hard dependency is 
`Promise` so it needs to be present some how in your project (polyfill or native).  
Compatible with NodeJS, CommonJS, AMD and Browser Globals.

## Install
Available on `npm`:
```bash
$ npm install async-arrays --save
```

and `bower`:
```bash
$ bower install async-arrays
```

### NodeJS
Install using `npm` Then:
```javascript
// ES5:
var PromiseArrays = require('async-arrays');

// ES6:
import PromiseArrays from 'async-arrays';

// Then Use:
PromiseArrays.filter(dummyArray, function() {
    // ...
});
```

### AMD
Install using `bower` or `npm` and include in your AMD project, then:
```javascript
// Include as dependency:
define(['async-arrays'], function (PromiseArrays) {
    // Then Use:
    PromiseArrays.filter(dummyArray, function() {
        // ...
    });
});
```

### Browser Globals
```html
<script src="/path/to/async-arrays.js"></script>
<script>
PromiseArrays.filter(dummyArray, function() {
    // ...
});
</script>
```

## Usage
TBA.

## License
This software is released under the [MIT License](http://sallar.mit-license.org/).  

    Copyright © 2015 Sallar Kaboli <sallar.kaboli@gmail.com>
    
    Permission is hereby granted, free of charge, to any person obtaining a copy
    of this software and associated documentation files (the “Software”), to deal
    in the Software without restriction, including without limitation the rights
    to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
    copies of the Software, and to permit persons to whom the Software is
    furnished to do so, subject to the following conditions:
    
    The above copyright notice and this permission notice shall be included in
    all copies or substantial portions of the Software.
    
    THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
    IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
    FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
    AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
    LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
    OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
    THE SOFTWARE.
    
[npm-url]: https://npmjs.com/package/promise-arrays
[travis-url]: https://travis-ci.org/sallar/promise-arrays
[npm-version-image]: https://img.shields.io/npm/v/promise-arrays.svg
[travis-build-image]: https://img.shields.io/travis/sallar/promise-arrays.svg

[license-url]: http://sallar.mit-license.org/
[license-image]: https://img.shields.io/npm/l/promise-arrays.svg