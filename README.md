# char

## Install

```
$ npm install char
```


## Usage

```js
const chr = require('char')

console.log(chr(65))
// => 'A'

console.log(chr(97))
// => 'a'

console.log(chr(8364))
// => '€'

console.log(chr(64))
// => '@'

console.log(chr(-1))
// => RangeError: Invalid code point -1
```
