# A ready to use localhost server

This tool simply start a localhost server in a node.js environment.

### Installation

To install it you need a node environment working with ```npm``` or another package manager like `yarn` or `bower`.

Just run the ```npm install``` to install all the node modules in the ```package.json file```.

You can also install them separately if you do not need all of them: ```npm install express``` (*required*), ```npm install dotenv``` and ```npm install body-parser```


### Configuration

Open the file ```server.js``` and configure your own listening port and the main file you want to be loaded by the localhost at startup.

You can also load a ```.env``` file that may load some variables that you can use in your environment (using the ```dotenv``` plugin) and/or parse incoming request bodies in a middleware (using the ```body-parser``` plugin). If you are not using these features you can comment/delete the dotenv and body-parser lines in the file.

### Start the localhost server

To start the localhost server, in the command line, go to the directory where the `server.js` file is placed and run:

```
node server
```

or, if you prefer,

```
npm start
```

To stop it just close the terminal window or type `CTRL + C`.
