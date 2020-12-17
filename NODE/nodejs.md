# Node.js Assessment:
![quote](images/Node.png?raw=true)

>### Q1. Which core module in Node provides an API to register callbacks to track asynchronous resources created inside a Node.js application?

- [ ] inspector

- [x] async_hooks

- [ ] dgram

- [ ] cluster

>### Q2. Which Node.js module should you use when you need to decode raw data into strings?

- [ ] buffer

- [ ] string_buffer

- [ ] util

- [x] string_decoder

>### Q3. Which choice is not a valid method on event emitters?

- [x] start

- [ ] on

- [ ] off

- [ ] once

>### Q4. What is the purpose of N-API?

- [ ] to execute multi-threaded code in the Node environment

- [X] to insulate Addons from changes in the underlying JavaScript engine

- [ ] to provide a quick way for users to create REST APIs

- [ ] to allow users to make requests to the server

>### Q5. Which statement about event emitters is false?

- [x] Event names must be camelCase strings.

- [ ] Any values returned by the listeners for an emitted event are ignored.

- [ ] The emit method allows an arbitrary set of arguments to be passed to the listener functions.

- [ ] When an event emitter object emits an event, all of the functions attached to that specific event are called synchronously.

>### Q6.How do you start a Node application, if the entry file is index.js?

- [x] node index.js

- [ ] node start

- [ ] nodemon start

- [ ] start index.js

>### Q7. Is it possible to write tests in Node.js without an external library?

- [ ] no

- [ ] yes, through the console module.

- [ ] yes, through the debugger module.

- [ ] yes, through the assert module

>### Q8. How do you make an HTTP server object active and listen to requests on certain ports?

- [x] server.listen

- [ ] server.run

- [ ] server.activate

- [ ] server.start

>### Q9. What does this code do?
```js
const fs = require('fs');
const os = require('os');

const system = os.platform();
const user = os.userInfo().username;

fs.appendFile('hello.txt', `Hello ${user} on ${system}!`, (err) => {
  if (err) throw err;
  console.log('The data was appended to file!');
});
```
- [ ] It logs system information.

- [x] It creates a text file named `hello.txt` and appends customized text.

- [ ] It creates a file named data and append numbers.

- [ ] It creates an image file.

>### Q10. What is one way to install npm packages?

- [ ] npm init` <nameofpackage>`

- [ ] install npm` <nameofpackage>`

- [x] npm install` <nameofpackage>`

- [ ] npm add` <nameofpackage>`

>### Q11. What is the purpose of the file system (fs) module?

- [ ] to provide methods to work with databases.

- [x] to provide methods to work with files.

- [ ] to add encryption to files.

- [ ] to provide methods to work with requests and responses

>### Q12. What response will you get when you send a get request to the server with this code?
```js
const http = require('http');

const hostname = '127.0.0.1';
const port = 3000;

const server = http.createServer((req, res) => {
  res.statusCode = 200;
  res.setHeader('Content-Type', 'text/plain');
  res.end('Hello World\n');
});

server.listen(port, hostname, () => {
  console.log(`Server running at http://${hostname}:${port}/`);
});
```
- [ ] server running at port 3000

- [ ] server running at` http://localhost:4000/`

- [ ] server running at `http://localhost:3000/`

- [x] server running at `http://127.0.0.1:3000/`

>### Q13. How can you delay the execution of the function fn by at least one second?

- [ ] delay(1000, fn);

- [ ] setDelay(fn, 1000);

- [ ] sleep(1000); fn;

- [x] setTimeout(fn, 1000);

>### Q14. What is the Node LTS version?

- [ ] It is the version with the latest features.

- [ ] It is an unstable version and is to be avoided.

- [x] It is the safest version for long-term support.

- [ ] It is the version that will be retired soon.

>### Q15. When you run JavaScript in a Node.js application, which element in a Node.js stack actually executes that JavaScript?

- [ ] the c-ares library

- [ ] the libuv library

- [x] the VM (like V8 or Chakra)

- [ ] the repl module

>### Q16. Is it possible to cluster multiple node processes?

- [ ] no

- [ ] yes, through the console module

- [ ] yes, through the assert module

- [x] yes, through the cluster module

>### Q17. What is the purpose of the path module?

- [ ] to provide utilities to test files

- [ ] to make network requests

- [x] to provide utilities to play with file and directory paths

- [ ] to provide utilities to add and remove filesto provide utilities to add and remove files

>### Q18.Which console method can be used to print the stack trace to the point of its execution?

- [ ] stack

- [x] trace

- [ ] debug

- [ ] print

>### Q19. Which of the following is a core module in Node?

- [ ] webpack

- [x] crypto 

- [ ] request

- [ ] chalk


>### Q20. Which special object is an instance of EventEmitter?

- [ ] process

- [ ] Buffer

- [ ] root

- [x] require

>### Q21. What is the shortest way to obtain the path name of the directory where your application is?

- [ ] console.log(path.dirname(__filename));

- [ ] console.log(dirname);

- [x] console.log(__dirname);

- [ ] console.log(__filename);

>### Q22. Which global object acts like a bridge between a Node script and the host operating system?

- [ ] env

- [ ] child_process

- [ ] v8 -

- [ ] process

>### Q23. Which DNS module method uses the underlying OS facilities and does not necessarily perform any network communication?

- [ ] reverse

- [ ] resolve4

- [x] lookup

- [ ] resolve

>### Q24. Which choice is a method on the console object?

- [ ] print

- [ ] test

- [ ] exit

- [x] time

>### Q25. What command would you use to count the number of logical CPUs on the machine that is running Node?

- [ ] node -p "process.cpus"

- [ ] node -p "process.os.cpus"

- [x] node -p "os.cpus().length"

- [ ] node -p "util.cpus().size"

>### Q26. If you run script.js with the following code, how do you access the value passed to VAR inside script.js? 
```js
VAR=value node script.js
```

- [ ] process.argv[VAR]

- [ ] process.env.VAR

- [x] process.argv[0]

- [ ] environment.VAR

>### Q27. Using ES6 imports, how would you import a module into a file?

- [ ] exports.thisModule = {….};

- [ ] npm install thisModule

- [x] import thismodule from ./thismodule;

- [ ] const thismodule = require(./thismodule);

>### Q28. What module would you use to encrypt data?

- [ ] Encrypt

- [x] Crypto

- [ ] Cryptic

- [ ] HTTP 

>### Q29. Which object holds all arguments passed after executing a script with the node command?

- [ ] os.arguments -

- [ ] process.argv

- [ ] process.arguments

- [ ] cli.args

>### Q30. Which choice is not a valid stream in Node?

- [ ] process.stdin

- [x] process.stdinfo

- [ ] process.stderr

- [ ] process.stdout

>### Q31. Which assert module method is usually used to test the error-first argument in callbacks?

- [ ] doesNotThrow

- [ ] deepStrictEqual

- [x] ifError

- [ ] fail

>### Q32. When a JavaScript function is invoked in Node, where is a new frame placed?

- [ ] the events queue

- [ ] the event loop

- [x] the call stack

- [ ] the poll phase

>### Q33. Which line imports a promise-based version of the readFile method?

- [ ] const { readFile } = require(fs).promises

- [ ] const { readFile } = require(promises)

- [ ] const { readFilePromise: readFile } = require(fs)

- [ ] const { readFile } = require(fs)

>### Q34. Which file does node-gyp use to read the build configuration of a module?

- [ ] binding.gyp

- [ ] gyp.json

- [ ] .gyprc

- [ ] package.gyp

>### Q35. What is the use of require?

- [ ] to load a module

- [ ] to create an object literal

- [ ] to create an application

- [ ] to add a callback function to an object

>### Q36. What is the package manager that comes with Node.js?

- [ ] GitHub

- [ ] Grunt

- [x] npm

- [ ] Gulp

>### Q37. Which library provides Node.js with the event loop?

- [x] V8

- [ ] events

- [ ] libuv

- [ ] c-ares

