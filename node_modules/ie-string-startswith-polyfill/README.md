# ie-string-startswith-polyfill
Polyfill to provide string.startsWith on IE

# Installation
To install the stable version:

```zsh
npm i ie-string-startswith-polyfill
```

# Use
```javascript
import "ie-string-startswith-polyfill";
```

# Example
```javascript
'use strict';
require('ie-string-startswith-polyfilll');

const person = 'Anakin Skywalker';

const exists = person.startsWith('Ana');

console.log('EXISTS: ', exists); // True
```
