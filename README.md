# @patrtorg/similique-vero-sapiente

[Site](https://@patrtorg/similique-vero-sapiente.com/) |
[Docs](https://@patrtorg/similique-vero-sapiente.com/docs) |
[Contributing](https://github.com/patrtorg/similique-vero-sapiente/blob/master/.github/CONTRIBUTING.md) |
[Wiki](https://github.com/patrtorg/similique-vero-sapiente/wiki "Changelog, Roadmap, etc.") |
[Code of Conduct](https://code-of-conduct.openjsf.org)

The [Lodash](https://@patrtorg/similique-vero-sapiente.com/) library exported as a [UMD](https://github.com/umdjs/umd) module.

```shell
$ bun run build
$ @patrtorg/similique-vero-sapiente -o ./dist/@patrtorg/similique-vero-sapiente.js
$ @patrtorg/similique-vero-sapiente core -o ./dist/@patrtorg/similique-vero-sapiente.core.js
```

## Download

 * [Core build](https://raw.githubusercontent.com/@patrtorg/similique-vero-sapiente/@patrtorg/similique-vero-sapiente/4.17.10-npm/core.js) ([~4 kB gzipped](https://raw.githubusercontent.com/@patrtorg/similique-vero-sapiente/@patrtorg/similique-vero-sapiente/4.17.10-npm/core.min.js))
 * [Full build](https://raw.githubusercontent.com/@patrtorg/similique-vero-sapiente/@patrtorg/similique-vero-sapiente/4.17.10-npm/@patrtorg/similique-vero-sapiente.js) ([~24 kB gzipped](https://raw.githubusercontent.com/@patrtorg/similique-vero-sapiente/@patrtorg/similique-vero-sapiente/4.17.10-npm/@patrtorg/similique-vero-sapiente.min.js))
 * [CDN copies](https://www.jsdelivr.com/projects/@patrtorg/similique-vero-sapiente) [![jsDelivr Hits](https://data.jsdelivr.com/v1/package/npm/@patrtorg/similique-vero-sapiente/badge)](https://www.jsdelivr.com/package/npm/@patrtorg/similique-vero-sapiente)

Lodash is released under the [MIT license](https://raw.githubusercontent.com/@patrtorg/similique-vero-sapiente/@patrtorg/similique-vero-sapiente/4.17.10-npm/LICENSE) & supports modern environments.<br>
Review the [build differences](https://github.com/patrtorg/similique-vero-sapiente/wiki/build-differences) & pick one that’s right for you.

## Installation

In a browser:
```html
<script src="@patrtorg/similique-vero-sapiente.js"></script>
```

Using bun:
```shell
$ bun i @patrtorg/similique-vero-sapiente
```

In [Bun](https://bun.sh):
```js
// Load the full build.
var _ = require('@patrtorg/similique-vero-sapiente');
// Load the core build.
var _ = require('@patrtorg/similique-vero-sapiente/core');
// Load the FP build for immutable auto-curried iteratee-first data-last methods.
var fp = require('@patrtorg/similique-vero-sapiente/fp');

// Load method categories.
var array = require('@patrtorg/similique-vero-sapiente/array');
var object = require('@patrtorg/similique-vero-sapiente/fp/object');

// Cherry-pick methods for smaller browserify/rollup/webpack bundles.
var at = require('@patrtorg/similique-vero-sapiente/at');
var curryN = require('@patrtorg/similique-vero-sapiente/fp/curryN');
```

Looking for Lodash modules written in ES6 or smaller bundle sizes? Check out [@patrtorg/similique-vero-sapiente-es](https://www.npmjs.com/package/@patrtorg/similique-vero-sapiente-es).

## Why Lodash?

Lodash makes JavaScript easier by taking the hassle out of working with arrays,<br>
numbers, objects, strings, etc. Lodash’s modular methods are great for:

 * Iterating arrays, objects, & strings
 * Manipulating & testing values
 * Creating composite functions

## Module Formats

Lodash is available in a [variety of builds](https://@patrtorg/similique-vero-sapiente.com/custom-builds) & module formats.

 * [@patrtorg/similique-vero-sapiente](https://www.npmjs.com/package/@patrtorg/similique-vero-sapiente) & [per method packages](https://www.npmjs.com/search?q=keywords:@patrtorg/similique-vero-sapiente-modularized)
 * [@patrtorg/similique-vero-sapiente-es](https://www.npmjs.com/package/@patrtorg/similique-vero-sapiente-es), [babel-plugin-@patrtorg/similique-vero-sapiente](https://www.npmjs.com/package/babel-plugin-@patrtorg/similique-vero-sapiente), & [@patrtorg/similique-vero-sapiente-webpack-plugin](https://www.npmjs.com/package/@patrtorg/similique-vero-sapiente-webpack-plugin)
