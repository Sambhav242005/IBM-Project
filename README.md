# IBM Project: JavaScript Type Coercion Example

## Overview

This is a simple JavaScript project that demonstrates how type coercion works in JavaScript. The project contains an `index.js` file with several `console.log()` statements showing the results of different operations involving strings, numbers, and booleans. These operations are designed to showcase how JavaScript automatically converts data types when performing operations.

The project is part of a college assignment for an IBM-related course that explores fundamental JavaScript concepts, especially type coercion.

## Project Files

### `index.js`

The `index.js` file contains the following operations:

```javascript
console.log("str(5) + num(4) =", "5" + 4); //str(54) 
console.log("str(5) - num(4) =", "5" - 4); //num(1)
console.log("str(5) - bool(true) =", "5" - true); // num(4)
console.log("num(5) + bool(true) =", 5 + true); // num(6)
console.log("num(5) + bool(false) =", 5 + false); // num(5)
```
