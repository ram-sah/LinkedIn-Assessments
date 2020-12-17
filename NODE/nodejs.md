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

>### Q38. How do you check that a value is a date object in Node?

- [x] util.types.isDate(value)

- [ ] assert.isDate(value)

- [ ] console.isDate(value)

- [ ] util.date(value)

>### Q39. Which CLI option can you use to debug a node script in Chrome DevTools?

- [ ] --dev-tools

- [x] --inspect

- [ ] --chrome

- [ ] --debug

>#### Q40. Which object is used to manage the cache of required modules?

- [ ] global.cache

- [ ] module.cache

- [ ] process.cache

- [x] require.cache 

>### Q41. If the child_process module methods are in scope, what is a current way to execute the command ps -ef using a child process?

- [ ] spawn("ps -ef")

- [x] exec("ps -ef")

- [ ] exec("ps", "-ef")

- [ ] fork("ps -ef")

>### Q42. When a request event is received in the HTTP module, what is the type of the first argument passed to that event, usually named req?

- [ ] http.IncomingMessage

- [ ] http.ServerRequest

- [ ] http.ClientRequest

- [ ] http.ServerResponse

>### Q43. You have a script.js file with the single line of code shown here. What will be the output of executing script.js with the node command?
```js
console.log(arguments);
``` 
- [ ] ReferenceError: arguments is not defined 

- [ ] an empty string 

- [ ] undefined 

- [x] an object representing an array that has five elements

>### Q44. If EventEmitter is in scope, which line of code will have an event emitter emitting a change event?

- [ ] EventEmitter.new().emit('change');

- [ ] new EventEmitter('change');

- [x] EventEmitter.emit('change');

- [ ] (new EventEmitter()).emit('change');

>### Q45. Which fs module method can be used to read the content of a file without buffering it in memory?

- [ ] read

- [ ] readFile

- [x] createReadStream 

- readFileSync

>### Q46. What can you export with module.exports?

- [ ] only variables and arrays

- [ ] only objects

- [ ] functions, objects, arrays, or anything you assign to the module

- [ ] only functions

>### Q47. What are the arguments passed to the module wrapper function?

- [ ] exports, process, require, module, __filename, __dirname

- [ ] exports, __filename, __dirname

- [ ] exports, module, __filename, __dirname

- [ ] exports, require, module, __filename, __dirname

>### Q48. How can you use the Promise API with a callback-based function such as child_process.exec?

- [ ] util.promisify(child_process.exec())

- [ ] util.promisify(child_process.exec)

- [ ] new Promise(child_process.exec())

- [ ] new Promise(child_process.exec)

>### Q49. Which choice is null a valid method on event emitters?

- [ ] start

- [ ] on

- [ ] once

- [ ] off

>### Q50. Which choice is not a Node repl command?

- [ ] .break

- [ ] .history

- [ ] .editor

- [ ] .save

>### Q51. Which object is a stream?

- [ ] process.uptime

- [ ] process

- [x] process.stdout

- [ ] Buffer

>### Q52. Which choice is a core module in Node?

- [ ] chalk

- [ ] crypto

- [ ] webpack

- [ ] request

>### Q53. What does the .node file extension represent?

- [ ] a JavaScript file that can have a .node extension as well as the .js extension

- [ ] a JSON file that can have a .node extension as well as the .json extension

- [ ] a C++ Addon file that is built with node-gyp

- [ ] a C++ file that can have a .node extension and that Node will be able to execute directly

>### Q54. What is the command to run the index.js file and silence all process warnings?

- [ ] node index.js --trace-warnings

- [ ] node index.js --no-warnings

- [ ] node --trace-warnings

- [ ] node --no-warnings

>### Q55. Which statement is true when you run the code shown below?

```js
require('child_process').fork('script.js');
```
- [ ] The forked process shares the event loop with the parent process

- [ ] A new VM instance is created and the two VM instances will be shared between the forked process and the parent process.

- [x] The forked process will have its own VM instance. 

- [ ] The forked process shares the same VM thread with the parent process.

>### Q56. Which core module in Node can you use to take advantage of multicore systems?

- [ ] cluster

- [ ] os

- [ ] util

- [ ] net

>### Q57. Which of the following Buffer class methods returns an uninitialized buffer?

- [x] allocUnsafe

- [ ] concat

- [ ] from

- [ ] alloc

>### Q58. What is the command to get a list of available commands for Node.js?

- [ ] node index.js -x
- [ ] node -v
- [ ] node -h
- [ ] node index.js -h

>### Q59. How do you run Node in strict mode?

- [ ] You have to use an external tool for that.

- [ ] You have to use ES modules.

- [ ] You have to use Chakra as the VM.

- [ ] Use the V8 option --use-strict.

>### Q60. Is it possible to create an https web server with Node.js?

- [ ] Yes, you can use the http module.

- [ ] Yes, you can use the https or http2 modules.

- [ ] No, there are no modules supporting it yet.

- [ ] Yes, you can use the path module.

>### Q61. What is one way to check that a value is a date object in Node?

- [ ] assert.isDate(value)

- [ ] util.types.isDate(value)

- [ ] util.date(value)

- [ ] console.isDate(value)

>### Q62. Which special object is an instance of EventEmitter?

- [ ] process

- [ ] Buffer

- [ ] root

- [ ] require

>### Q63. Which module variable holds the resolved aboslute path of the current module file?

- [ ] __pathname
- [ ] __location
- [ ] __flder
- [x] __filename
