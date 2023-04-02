---Number 1---
An event loop is responsible for executing javascript code, collecting and processing events, and executing queued sub-tasks. 

---Number 2---
i.   Timers- this phase executes callbacks scheduled by setTimeout() and setInterval(). 
ii.  Pending callbacks- this phase executes I/O callbacks deferred to the next loop iteration.
iii. Idle, prepare- this is only used internally.
iv.  Poll- retrieve new I/O events; execute I/O related callbacks (almost all with the exception of close callbacks, the ones   scheduled by timers, and setImmediate()); node will block here when appropriate.
v.   Check-  setImmediate() callbacks are invoked here.
vi.  Close callback-  some close callbacks, e.g. socket.on('close', ...).

---Number 3---
i.   Focus on Code Quality.
ii.  Prefer ES6+ and Async/Await.
iii. Keep Code Small.
iv.  Handle Errors.
 
---Number 4---
NPM is both a tool for managing project dependencies via command line and a website hosting more than 1 million third-party packages that can be used for your project.

To initialize npm and go through all of the settings use:
$ npm init

To automatically select all defaults use -y
$ npm init -y

---Number 5---
To run a script that you have added to your package.json file, simply run $ npm run argument with the name of the script as the argument.
$ npm run prettier




