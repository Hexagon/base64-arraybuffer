# base64-arraybuffer

![CI](https://github.com/niklasvh/base64-arraybuffer/workflows/CI/badge.svg?branch=master)
[![NPM Downloads](https://img.shields.io/npm/dm/base64-arraybuffer.svg)](https://www.npmjs.org/package/base64-arraybuffer)
[![NPM Version](https://img.shields.io/npm/v/base64-arraybuffer.svg)](https://www.npmjs.org/package/base64-arraybuffer)

Encode/decode base64 or base64url data into ArrayBuffers.

This is basically [github.com/niklasvh/base64-arraybuffer](https://github.com/niklasvh/base64-arraybuffer), but with added base64url support.

### Installing
You can install the module via npm:

    npm install @hexagon/base64-arraybuffer
  
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
