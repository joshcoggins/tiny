# @jcoggins/tiny

[![npm (scoped)](https://img.shields.io/npm/v/@rocketly/tiny.svg)](https://www.npmjs.com/package/@rocketly/tiny)
[![npm bundle size (minified)](https://img.shields.io/bundlephobia/min/@rocketly/tiny.svg)](https://www.npmjs.com/package/@rocketly/tiny)

Removes all spaces from a string.

## Install
```
$ npm install @rocketly/tiny
```

## Usage
```js
const tiny = require("@rocketly/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```