# Node.js Interview Questions and Answers

**1. What is Node.js?**

**Answer:** Node.js is a runtime environment built on Chrome's V8 JavaScript engine. It allows you to execute JavaScript code outside of a web browser, primarily used for server-side development.

**2. What is the event loop in Node.js?**

**Answer:** The event loop is the core of Node.js's non-blocking, asynchronous I/O model. It continuously checks the call stack and the event queue. If the call stack is empty, it takes the first event from the event queue and pushes its associated callback function onto the call stack for execution.

**3. What is `npm`? What is its purpose?**

**Answer:** `npm` (Node Package Manager) is the default package manager for Node.js. It allows you to easily install, share, and manage dependencies (libraries and tools) for your Node.js projects.

**4. What are streams in Node.js?**

**Answer:** Streams are a way to handle reading and writing data in Node.js.  They allow you to process data piece by piece, without loading the entire data into memory.  This is very efficient when handling large amounts of data.

**5. What is middleware in Express.js?**

**Answer:** Middleware functions are functions that have access to the request object (req), response object (res), and the next middleware function in the application's request-response cycle.  They can modify the request and response objects, end the request-response cycle, or call the next middleware function in the stack.

**6. What is the difference between `process.nextTick()` and `setImmediate()`?**
   Both are used to defer the execution of a function.

* `process.nextTick()`: Adds the callback to the next tick of the event loop.  It will be executed right after the current operation completes, before the event loop continues.
* `setImmediate()`: Adds the callback to the immediate queue. It will be executed in the next iteration of the event loop, after any I/O operations.