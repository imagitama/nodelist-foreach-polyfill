# NodeList.forEach polyfill

Provides a polyfill for [Nodelist.prototype.forEach()](https://developer.mozilla.org/en-US/docs/Web/API/NodeList/forEach) to all Browsers supporting [ES5](https://caniuse.com/#search=es5).

## Native support

Chrome 51, Firefox 50, Opera 38, Safari 10<br>
Android Browser none, IE Mobile none, IE none<br>
See [MDN](https://developer.mozilla.org/en-US/docs/Web/API/NodeList/forEach) for more information.

## Import

```
// CommonJS
require('nodelist-foreach-polyfill');

// ES6 Modules
import 'nodelist-foreach-polyfill';
```

## Usage

```
// Get Nodelist from DOM via document.querySelectorAll()
var elements = document.querySelectorAll('.foo');

// Loop through nodelist
elements.forEach(function(element, index, nodelist) {
    console.log(this, element, index, nodelist);
});
```
