# js-datasets-iris

Package provides the "Iris dataset for javascript

# Install

```bash
npm install js-datasets-iris
```

# Usage

In nodejs 


```javascript
var iris = require('js-datasets-iris')

// == PRITN ROW COUNT == //
console.log(iris.rowCount);

// == PRINT ALL DATA in the format of [[sepalLength, sepalWidth, petalLength, petalWidth, specisies], ...] == //
console.log(iris.data);

// == PRINT the sepalLength == //
console.log(iris.sepalLength);

// == PRINT the sepalWidth == //
console.log(iris.sepalWidth);

// == PRINT the petalLength == //
console.log(iris.petalLength);

// == PRINT the petalWidth == //
console.log(iris.petalWidth);

```

In HTML

Include the "node_modules/js-datasets-iris/build/jsiris.min.js" (or "node_modules/js-datasets-iris/src/jsiris.js") in your HTML \<script\> tag

```javascript
// == PRITN ROW COUNT == //
console.log(jsIris.rowCount);

// == PRINT ALL DATA in the format of [[sepalLength, sepalWidth, petalLength, petalWidth, specisies], ...] == //
console.log(jsIris.data);

// == PRINT the sepalLength == //
console.log(jsIris.sepalLength);

// == PRINT the sepalWidth == //
console.log(jsIris.sepalWidth);

// == PRINT the petalLength == //
console.log(jsIris.petalLength);

// == PRINT the petalWidth == //
console.log(jsIris.petalWidth);
```
