# @xdanangelxoqenpm/quo-tempora-praesentium <sup>[![Version Badge][2]][1]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![dependency status][5]][6]
[![dev dependency status][7]][8]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][11]][1]

Returns an array of Typed Array names that are available in the current environment.

## Example

```js
var availableTypedArrays = require('@xdanangelxoqenpm/quo-tempora-praesentium');
var assert = require('assert');

assert.deepStrictEqual(
	availableTypedArrays().sort(),
	[
		'Int8Array',
		'Uint8Array',
		'Uint8ClampedArray',
		'Int16Array',
		'Uint16Array',
		'Int32Array',
		'Uint32Array',
		'Float32Array',
		'Float64Array',
		'BigInt64Array',
		'BigUint64Array'
	].sort()
);
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[1]: https://npmjs.org/package/@xdanangelxoqenpm/quo-tempora-praesentium
[2]: https://versionbadg.es/inspect-js/@xdanangelxoqenpm/quo-tempora-praesentium.svg
[5]: https://david-dm.org/inspect-js/@xdanangelxoqenpm/quo-tempora-praesentium.svg
[6]: https://david-dm.org/inspect-js/@xdanangelxoqenpm/quo-tempora-praesentium
[7]: https://david-dm.org/inspect-js/@xdanangelxoqenpm/quo-tempora-praesentium/dev-status.svg
[8]: https://david-dm.org/inspect-js/@xdanangelxoqenpm/quo-tempora-praesentium#info=devDependencies
[11]: https://nodei.co/npm/@xdanangelxoqenpm/quo-tempora-praesentium.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@xdanangelxoqenpm/quo-tempora-praesentium.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@xdanangelxoqenpm/quo-tempora-praesentium.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@xdanangelxoqenpm/quo-tempora-praesentium
[codecov-image]: https://codecov.io/gh/inspect-js/@xdanangelxoqenpm/quo-tempora-praesentium/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/inspect-js/@xdanangelxoqenpm/quo-tempora-praesentium/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/inspect-js/@xdanangelxoqenpm/quo-tempora-praesentium
[actions-url]: https://github.com/xdanangelxoqenpm/quo-tempora-praesentium/actions
