# A ready to use localhost server

This tool simply start a localhost server in a node.js environment.

### Installation

To install it you need a node environment working with ```npm``` or another package installer. Just running the ```npm install``` it will install the dependencies in the ```package.json file``` that are: ```express```, ```dotenv``` and ```body-parser```


### Configuration

Open the file ```server.js``` and configure your own listening port and the main file you want to be loaded by the localhost at startup.

You can also load a ```.env``` file that may load some variables that you can use in your environment (using the ```dotenv``` plugin) and/or parse incoming request bodies in a middleware (using the ```body-parser``` plugin). If you are not using these features you can comment/delete the dotenv and body-parser lines in the file.

### Start the localhost server

To run it, in a command line, go to the directory where the file is placed and run this command:

```
node server
```
