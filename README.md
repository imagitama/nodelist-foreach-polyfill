# NodeList.forEach polyfill

Simple polyfill for the `NodeList.forEach` method.

It means you can use `forEach` on `document.querySelectorAll` and other similar functions that return `NodeList`.

## Native support
Chrome 51, Firefox 50, Opera 38, Safari 10

Android Browser none, IE Mobile none, IE none

See [MDN](https://developer.mozilla.org/en-US/docs/Web/API/NodeList/forEach)

## Usage

Import before any usages of `document.querySelectorAll("#foo").forEach((elem) => { ... })` etc