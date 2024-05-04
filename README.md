# @zitterorg/cupiditate-fugiat-culpa <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

Get the byte length of an ArrayBuffer, even in engines without a `.byteLength` method.

## Example

```js
const assert = require('assert');
const byteLength = require('@zitterorg/cupiditate-fugiat-culpa');

assert.equal(byteLength([]), NaN, 'an array is not an ArrayBuffer, yields NaN');

assert.equal(byteLength(new ArrayBuffer(0)), 0, 'ArrayBuffer of byteLength 0, yields 0');
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[package-url]: https://npmjs.org/package/@zitterorg/cupiditate-fugiat-culpa
[npm-version-svg]: https://versionbadg.es/inspect-js/@zitterorg/cupiditate-fugiat-culpa.svg
[deps-svg]: https://david-dm.org/inspect-js/@zitterorg/cupiditate-fugiat-culpa.svg
[deps-url]: https://david-dm.org/inspect-js/@zitterorg/cupiditate-fugiat-culpa
[dev-deps-svg]: https://david-dm.org/inspect-js/@zitterorg/cupiditate-fugiat-culpa/dev-status.svg
[dev-deps-url]: https://david-dm.org/inspect-js/@zitterorg/cupiditate-fugiat-culpa#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@zitterorg/cupiditate-fugiat-culpa.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@zitterorg/cupiditate-fugiat-culpa.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@zitterorg/cupiditate-fugiat-culpa.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@zitterorg/cupiditate-fugiat-culpa
[codecov-image]: https://codecov.io/gh/inspect-js/@zitterorg/cupiditate-fugiat-culpa/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/inspect-js/@zitterorg/cupiditate-fugiat-culpa/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/inspect-js/@zitterorg/cupiditate-fugiat-culpa
[actions-url]: https://github.com/zitterorg/cupiditate-fugiat-culpa/actions
