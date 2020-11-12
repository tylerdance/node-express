# node-express
## Node

1. In terminal, enter `npm init` to create package OR enter `npm init -y` to autofill form
2. Fill out form
3. Create `index.js` file
4. Create `module.js` file
5. Export your functions from your `module.js` by creating an object
```js
module.exports = {
    add,
    subtract
}
```
6. In your main Javascript file (i.e. `index.js`), `require` your functions
```js
const { add, subtract } = require("./myModule");
```