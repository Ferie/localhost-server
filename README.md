# A ready to use localhost server

This tool is a ready to use localhost Node server.

## Installation

To install it you need a node environment working with `npm` or any another package manager (e.g. `yarn`).

Just run the `npm i` to install all the node modules in the `package.json` file.

You can also install them separately if you do not need all of them: `npm install express` (*required*), `npm install dotenv` and `npm install body-parser`


## Configuration

Open the `server.js` file and configure your own listening port and the main file you want to be loaded by the localhost at startup.

As this server is using the [`dotenv` plugin](https://www.npmjs.com/package/dotenv), you can also load a `.env` file to load some variables that you may use in your environment.

If you decide also to install the [`body-parser` plugin](https://www.npmjs.com/package/body-parser) you may also parse incoming request bodies in a middleware before your handlers.

If you are not using these features you can comment/delete the lines that are referred to dotenv and body-parser.

## Start the localhost server

To start the localhost server in the terminal, go to the directory where the `server.js` file is located and run:
```
node server
```

or, if you prefer,
```
npm start
```

To stop it just close the terminal window or press `CTRL + C`.
