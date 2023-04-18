# @manoj-aviox/tiny

[![npm (scoped)](https://img.shields.io/npm/v/@manoj-aviox/tiny.svg)](https://www.npmjs.com/package/@manoj-aviox/tiny)
[![npm bundle size (minified)](https://img.shields.io/bundlephobia/min/@manoj-aviox/tiny.svg)](https://www.npmjs.com/package/@manoj-aviox/tiny)

Removes all spaces from a string.

## Install

```
$ npm install @manoj-aviox/tiny
```

## Usage

```js
const tiny = require("@manoj-aviox/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```
