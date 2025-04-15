# JavaScript Interview Questions and Answers

**1. What is the difference between `var`, `let`, and `const`?**

* `var`: Has function scope or global scope if declared outside a function. It can be redeclared and reassigned.
* `let`: Has block scope. It can be reassigned but not redeclared within the same scope.
* `const`: Has block scope. It cannot be reassigned or redeclared after initialization.

**2. What are closures in JavaScript?**

**Answer:** A closure is a function that "remembers" its lexical environment (the environment in which it was created) even when it is executed outside that environment. This allows the inner function to access variables from the outer function's scope.

**3. What is the difference between `==` and `===` in JavaScript?**

* `==` (loose equality) compares values after performing type coercion if necessary.
* `===` (strict equality) compares values without type coercion. It returns `true` only if both the value and the type are the same.

**4. What are Promises?**

**Answer:** A Promise is an object that represents the eventual completion (or failure) of an asynchronous operation and its resulting value.  It can be in one of three states: pending, fulfilled, or rejected.

**5. What is the event loop?**

**Answer:** The event loop is a mechanism that allows JavaScript to be non-blocking.  It continuously monitors the call stack and the message queue.  If the call stack is empty, the event loop takes the first message from the queue and pushes it onto the call stack to be executed.

**6. What are higher-order functions?**

**Answer:** Higher-order functions are functions that operate on other functions, either by taking them as arguments or by returning them.  Examples include `map()`, `filter()`, and `reduce()`.