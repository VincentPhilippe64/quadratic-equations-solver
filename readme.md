# quadratic-equations-solver
NPM module to solve quadratic equations.

## Install
```npm i quadratic-equations-solver```

## Use
The equation has to be under the **ax²+bx+c=0** form.
Example:
```javascript
const solve = require("quadratic-equations-solver");

var a = '1';
var b = '-12';
var c = '-28';
var solutions = solve(a, b, c);
var solution1 = solutions[0];  // Give you the first solution possible
var solution2 = solutions[1];  // Give you the second solution possible
var discriminant = solutions[2];  // Give you the discriminant (b²-4ac)
```
**NOTE:** If the discriminant is equal to zero, only one solution will possible, which means *solution1* and *solution2* will have the same value.
