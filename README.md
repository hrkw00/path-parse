# path-parse [![Build Status](https://travis-ci.org/jbgutierrez/path-parse.svg?branch=master)](https://travis-ci.org/jbgutierrez/path-parse)

> Node.js 0.11.15 [`path.parse(pathString)`](https://nodejs.org/api/path.html#path_path_parse_pathstring) ponyfill.

> Ponyfill: A polyfill that doesn't overwrite the native method

## Install

```
$ npm install --save path-parse
```

## Usage

```js
var pathParse = require('path-parse');

pathParse('/home/user/dir/file.txt');
//=> {
//       root : "/",
//       dir : "/home/user/dir",
//       base : "file.txt",
//       ext : ".txt",
//       name : "file"
//   }
```

## API

See [`path.parse(pathString)`](https://nodejs.org/api/path.html#path_path_parse_pathstring) docs.

### pathParse(path)

### pathParse.posix(path)

The Posix specific version.

### pathParse.win32(path)

The Windows specific version.

## License

MIT © [Javier Blanco](http://jbgutierrez.info)