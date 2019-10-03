# Example Async Node C++ Addon

Allows for non-blocking C++ operations from Node.js using the callback pattern.

Lightweight example.

Tested in Node.js v12.11.1 on Linux


## Usage

Clone this git repo and navigate to the project directory. Follow the commands below:

```bash
$ npm install -g node-gyp
$ cd async-addon
$ node-gyp configure
$ node-gyp build
$ cd ..
$ node index.js
$ node doAsync.js
```

## Credits

Thanks to Scott Frees' [C++ processing from Node.js - Part 4 - Asynchronous addons](https://blog.scottfrees.com/c-processing-from-node-js-part-4-asynchronous-addons) article for a lot of help.

