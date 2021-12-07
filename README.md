# @hexagon/base64-arraybuffer

![CI](https://github.com/hexagon/base64-arraybuffer/workflows/CI/badge.svg?branch=master)
[![NPM Version](https://img.shields.io/npm/v/@hexagon/base64-arraybuffer.svg)](https://www.npmjs.org/package/@hexagon/base64-arraybuffer)
[![NPM Downloads](https://img.shields.io/npm/dm/@hexagon/base64-arraybuffer.svg)](https://www.npmjs.org/package/@hexagon/base64-arraybuffer)
[![](https://data.jsdelivr.com/v1/package/npm/@hexagon/base64-arraybuffer/badge)](https://www.jsdelivr.com/package/npm/@hexagon/base64-arraybuffer)

Encode/decode base64 or base64url data into ArrayBuffers.

This is basically [github.com/niklasvh/base64-arraybuffer](https://github.com/niklasvh/base64-arraybuffer), but with added base64url support.

### Installing

#### Node 
You can install the module via npm:

```npm install @hexagon/base64-arraybuffer```

```javascript
const base64 = require('@hexagon/base64-arraybuffer');

const result = base64.encode("Hello World!");
const resultUrl = base64.encode("Hello World!", true);
```

#### CDN / Browser / Deno

[www.jsdelivr.com/package/npm/@hexagon/base64-arraybuffer?path=dist](https://www.jsdelivr.com/package/npm/@hexagon/base64-arraybuffer?path=dist)

In a browser, you normally want ```/dist/base64-arraybuffer.umd.js``` which will register a global object named ```base64``` 

```javascript
// Global object base64 available

const result = base64.encode("Hello World!");
const resultUrl = base64.encode("Hello World!", true);
```

## API

The library encodes and decodes base64/base64url to and from ArrayBuffers

 - __encode(buffer)__ - Encodes `ArrayBuffer` into base64 string
 - __decode(str)__ - Decodes base64 string to `ArrayBuffer`

 - __encode(buffer, true)__ - Encodes `ArrayBuffer` into base64url string
 - __decode(str, true)__ - Decodes base64url string to `ArrayBuffer`

### Testing

You can run the test suite with:

    npm test

## License
Copyright (c) 2021 Hexagon
Licensed under the MIT license.

Copyright (c) 2012 Niklas von Hertzen
Licensed under the MIT license.
