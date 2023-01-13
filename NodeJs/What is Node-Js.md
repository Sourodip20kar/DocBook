# Node.Js
Node.js is an open source server environment this allows us to run JavaScript on the server.
## why Node.js?

**Node.js uses asynchronous programming**

**NodeJS is a runtime environment that runs on Chrome's V8 Engine <small>(V8 is Google’s open source high-performance JavaScript and WebAssembly engine, written in C++. It is used in Chrome and in Node.js, among others i.e. it parses and executes JavaScript code)</small>**

**Running JavaScript outside DOM Content is Node.js**

A common task for a web server can be to open a file on the server and return the content to the client.

* A Node.js app runs in a single process, without creating a new thread for every request. 

* Node.js provides a set of asynchronous I/O primitives in its standard library that prevent JavaScript code from blocking and generally, libraries in Node.js are written using non-blocking paradigms, making blocking behavior the exception rather than the norm, which is very memory efficient.

* Ready to handle the next request.

* When the file system has opened and read the file, the server returns the content to the client.

* Node.js eliminates the waiting, and simply continues with the next request.

**While the other server sites such as PHP or ASP handles a file request:**
1. Sends the task to the computer's file system.
2. Waits while the file system opens and reads the file.
3. Returns the content to the client.
4. Ready to handle the next request.
