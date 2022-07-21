# lazy-code
Super short names and structures. Generator of normal code.

## Installing

Using npm:

```bash
$ npm install lazy-code
```

## Example

```js
import { l } from 'lazy-code';

l('hello') // => hello
l('hello').place() // => hello + line of code and path to file
```

