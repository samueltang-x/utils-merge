# utils-merge

Merges the properties from a source object into a destination object.

Status:
[![Version](https://img.shields.io/npm/v/utils-merge.svg?label=version)](https://www.npmjs.com/package/utils-merge)
[![Build](https://img.shields.io/travis/jaredhanson/utils-merge.svg)](https://travis-ci.org/jaredhanson/utils-merge)
[![Quality](https://img.shields.io/codeclimate/github/jaredhanson/utils-merge.svg?label=quality)](https://codeclimate.com/github/jaredhanson/utils-merge)
[![Coverage](https://img.shields.io/coveralls/jaredhanson/utils-merge.svg)](https://coveralls.io/r/jaredhanson/utils-merge)
[![Dependencies](https://img.shields.io/david/jaredhanson/utils-merge.svg)](https://david-dm.org/jaredhanson/utils-merge)


## Install

```bash
$ npm install utils-merge
```

## Usage

```javascript
var a = { foo: 'bar' }
  , b = { bar: 'baz' };

merge(a, b);
// => { foo: 'bar', bar: 'baz' }
```

## License

[The MIT License](http://opensource.org/licenses/MIT)

Copyright (c) 2013-2017 Jared Hanson <[http://jaredhanson.net/](http://jaredhanson.net/)>


