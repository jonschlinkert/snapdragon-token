# snapdragon-token [![NPM version](https://img.shields.io/npm/v/snapdragon-token.svg?style=flat)](https://www.npmjs.com/package/snapdragon-token) [![NPM monthly downloads](https://img.shields.io/npm/dm/snapdragon-token.svg?style=flat)](https://npmjs.org/package/snapdragon-token) [![NPM total downloads](https://img.shields.io/npm/dt/snapdragon-token.svg?style=flat)](https://npmjs.org/package/snapdragon-token) [![Linux Build Status](https://img.shields.io/travis/here-be-snapdragons/snapdragon-token.svg?style=flat&label=Travis)](https://travis-ci.org/here-be-snapdragons/snapdragon-token)

> Create a snapdragon token. Used by the snapdragon lexer, but can also be used by plugins.

Please consider following this project's author, [Jon Schlinkert](https://github.com/jonschlinkert), and consider starring the project to show your :heart: and support.

## Install

Install with [npm](https://www.npmjs.com/):

```sh
$ npm install --save snapdragon-token
```

## Usage

```js
const Token = require('snapdragon-token');
```

## API

**Params**

* `type` **{String|Object}**: The token type to use when `val` is a string.
* `val` **{String}**: Value to set
* `returns` **{Object}**: Token instance

**Example**

```js
const token = new Token('*', 'Star');
const token = new Token({type: 'star', val: '*'});
console.log(token) //=> Token { type: 'star', val: '*' }
```

## About

<details>
<summary><strong>Contributing</strong></summary>

Pull requests and stars are always welcome. For bugs and feature requests, [please create an issue](../../issues/new).

Please read the [contributing guide](.github/contributing.md) for advice on opening issues, pull requests, and coding standards.

</details>

<details>
<summary><strong>Running Tests</strong></summary>

Running and reviewing unit tests is a great way to get familiarized with a library and its API. You can install dependencies and run tests with the following command:

```sh
$ npm install && npm test
```

</details>

<details>
<summary><strong>Building docs</strong></summary>

_(This project's readme.md is generated by [verb](https://github.com/verbose/verb-generate-readme), please don't edit the readme directly. Any changes to the readme must be made in the [.verb.md](.verb.md) readme template.)_

To generate the readme, run the following command:

```sh
$ npm install -g verbose/verb#dev verb-generate-readme && verb
```

</details>

### Related projects

You might also be interested in these projects:

* [snapdragon-node](https://www.npmjs.com/package/snapdragon-node): Snapdragon utility for creating a new AST node in custom code, such as plugins. | [homepage](https://github.com/jonschlinkert/snapdragon-node "Snapdragon utility for creating a new AST node in custom code, such as plugins.")
* [snapdragon-util](https://www.npmjs.com/package/snapdragon-util): Utilities for the snapdragon parser/compiler. | [homepage](https://github.com/jonschlinkert/snapdragon-util "Utilities for the snapdragon parser/compiler.")
* [snapdragon](https://www.npmjs.com/package/snapdragon): Easy-to-use plugin system for creating powerful, fast and versatile parsers and compilers, with built-in source-map… [more](https://github.com/jonschlinkert/snapdragon) | [homepage](https://github.com/jonschlinkert/snapdragon "Easy-to-use plugin system for creating powerful, fast and versatile parsers and compilers, with built-in source-map support.")

### Author

**Jon Schlinkert**

* [linkedin/in/jonschlinkert](https://linkedin.com/in/jonschlinkert)
* [github/jonschlinkert](https://github.com/jonschlinkert)
* [twitter/jonschlinkert](https://twitter.com/jonschlinkert)

### License

Copyright © 2017, [Jon Schlinkert](https://github.com/jonschlinkert).
Released under the [MIT License](LICENSE).

***

_This file was generated by [verb-generate-readme](https://github.com/verbose/verb-generate-readme), v0.6.0, on November 30, 2017._