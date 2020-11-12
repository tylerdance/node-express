# node-express
## Node

1. After navigating to your project directory in terminal, enter `npm init` to create json pkg OR enter `npm init -y` to create pkg and autofill form
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
6. In your main Javascript file (i.e. `main.js`), `require` your functions
```js
const { add, subtract } = require("./module");
```