# @sooraj/tiny

[![npm (scoped)](https://img.shields.io/npm/v/@sooraj/tiny.svg)](https://www.npmjs.com/package/@sooraj/tiny)
[![npm bundle size (minified)](https://img.shields.io/bundlephobia/min/@sooraj/tiny.svg)](https://www.npmjs.com/package/@sooraj/tiny)

Removes all spaces from a string.

## Install

```
$ npm install @sooraj/tiny
```

## Usage

```js
const tiny = require("@sooraj/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```
