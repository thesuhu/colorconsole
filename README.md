# colorconsole

![GitHub package.json version](https://img.shields.io/github/package-json/v/thesuhu/colorconsole?style=flat-square)
[![license](https://img.shields.io/github/license/thesuhu/colorconsole?style=flat-square)](https://github.com/thesuhu/colorconsole/blob/master/LICENSE)

Make console log more colorful. This module provides four templates namely regular log, error log, HTTP log and SQL log.

## Install

```sh
npm install @thesuhu/colorconsole --save-dev
```

## Usage

Below is an example regular and error log.
```js
const { logConsole, errorConsole } = require('../colorconsole')

// ordinary log
logConsole('Hello world!')

// error log
errorConsole('A very cool error here')
```
Below is an example HTTP log.
```js
// to do
```
Below is an example SQL log.
```js
// to do
```

## Credits

- [Chalk](https://www.npmjs.com/package/chalk)

## License

[MIT](https://github.com/thesuhu/colorconsole/blob/master/LICENSE)