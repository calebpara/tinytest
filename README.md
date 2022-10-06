# tinytest

Removes all spaces from a string.

## Install

```
$ npm install @calebpara/tinytest
```

## Usage

```js
const tiny = require("@calebpara/tinytest");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```