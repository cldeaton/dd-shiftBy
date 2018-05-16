# dd-shiftBy

The package, when required, adds a "shiftBy" method to the Array prototype. The method should shift each element of the array by n spaces.

### Installing

```
npm install --save dd-shiftby
```

And in Node:

```
var shiftBy = require('dd-shiftby');
var arr = [];

arr.shiftBy(number);
```

## Examples

```
[1, 2, 3].shiftBy(1); // outputs [3, 1, 2]
```

```
[1, 2, 3].shiftBy(-4); // outputs [2, 3, 1]
```


## Authors

* **Chris Deaton** - [cldeaton](https://github.com/cldeaton)
