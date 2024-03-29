# Example Async Node C++ Addon - Nodejs@latest

Allows for non-blocking C++ operations from Node.js using the callback pattern.

Lightweight example.

Tested in @latest cutting-bleeding-edge Node.js v12.12.0 version on (excellent) openSUSE Tumbleweed Linux


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

Thanks to Paul Hauner [https://github.com/paulhauner/example-async-node-addon](https://github.com/paulhauner/example-async-node-addon) for the first version of the source code.

Thanks to Scott Frees' [C++ processing from Node.js - Part 4 - Asynchronous addons](https://blog.scottfrees.com/c-processing-from-node-js-part-4-asynchronous-addons) article for a lot of help.

