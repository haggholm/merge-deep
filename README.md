# merge-deep [![NPM version](https://badge.fury.io/js/merge-deep.svg)](http://badge.fury.io/js/merge-deep)


> Recursively merge values in a javascript object.

Based on [mout's](https://github.com/mout/mout) implementation of merge

## Install
#### Install with [npm](npmjs.org):

```bash
npm i merge-deep --save-dev
```

## Run tests

```bash
npm test
```

## Usage

```js
var merge = require('merge-deep');

merge({a: {b: {c: 'c', d: 'd'}}}, {a: {b: {e: 'e', f: 'f'}}});
//=> { a: { b: { c: 'c', d: 'd', e: 'e', f: 'f' } } }
```
## Author

**Jon Schlinkert**
 
+ [github/jonschlinkert](https://github.com/jonschlinkert)
+ [twitter/jonschlinkert](http://twitter.com/jonschlinkert) 

### Related projects

These are other projects I maintain:

  - [arrayify-compact](https://github.com/jonschlinkert/arrayify-compact)
  - [compact-object](https://github.com/jonschlinkert/compact-object)
  - [delete](https://github.com/jonschlinkert/delete)
  - [flatten-object](https://github.com/jonschlinkert/flatten-object)
  - [for-in](https://github.com/jonschlinkert/for-in)
  - [for-own](https://github.com/jonschlinkert/for-own)
  - [has-any](https://github.com/jonschlinkert/has-any)
  - [has-value](https://github.com/jonschlinkert/has-value)
  - [is-number](https://github.com/jonschlinkert/is-number)
  - [is-plain-object](https://github.com/jonschlinkert/is-plain-object)
  - [mixin-deep](https://github.com/jonschlinkert/mixin-deep)
  - [mixin-object](https://github.com/jonschlinkert/mixin-object)
  - [object-length](https://github.com/jonschlinkert/object-length)
  - [omit-empty](https://github.com/jonschlinkert/omit-empty)
  - [reduce-object](https://github.com/jonschlinkert/reduce-object)

## License
Copyright (c) 2014 Jon Schlinkert, contributors.  
Released under the MIT license

***

_This file was generated by [verb-cli](https://github.com/assemble/verb-cli) on October 07, 2014._