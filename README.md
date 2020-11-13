# node-express
## Node
### Function modules

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

### Create and Import Node Modules
1. Determine if the `npm` you need is something that should be installed gloablly on your machine, or if you only need it for the app currently at hand.
2. Global install: `npm i -g [name of npm]` | Local install: `npm i [name of npm]`
3. `require` the npm in your main Javascript file (i.e. `index.js`)
```js
const luxon = require('luxon');
```
4. Log anything from the npm in your terminal with the command, `node index.js`, or `node` + [`name of your main js file`]
5. Add a `.gitignore` file and include your `node_modules/` folders so that they do not push to github along with your other files