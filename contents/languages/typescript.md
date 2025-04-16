# TypeScript Interview Questions and Answers

**1. What is TypeScript? What are its benefits?**

**Answer:** TypeScript is a superset of JavaScript that adds optional static typing to the language.

**Benefits:**

* Improved code readability and maintainability due to explicit types.
* Early detection of errors during development, reducing runtime issues.
* Enhanced tooling and IDE support (e.g., autocompletion, type checking).
* Better collaboration among developers due to clear type contracts.

**2. What are interfaces and types in TypeScript? How do they differ?**

**Answer:** Both interfaces and types are used to define the shape of objects in TypeScript.

* **Interfaces:** Primarily used to define the structure of objects. They can be open for declaration merging (multiple declarations with the same name are merged).
* **Types:** More versatile and can define aliases for primitive types, unions, intersections, and more. They are generally closed for declaration merging.

**3. What are generics in TypeScript?**

**Answer:** Generics allow you to write reusable code that can work with different types without losing type safety. They provide a way to parameterize types, similar to how functions parameterize values.

**4. What are decorators in TypeScript?**

**Answer:** Decorators are a special kind of declaration that can be attached to a class declaration, method, accessor, property, or parameter.  They use the `@expression` syntax.  Decorators provide a way to add both annotations and a meta-programming syntax for class declarations and members.

**5. What are namespaces in TypeScript?**

**Answer:** Namespaces (formerly "internal modules") are a way to organize code within a TypeScript application.  They provide a way to create a scope for variables, functions, and classes, preventing naming collisions.  Modules are now preferred.

**6. What are union types in TypeScript?**

**Answer:** A union type describes a value that can be one of several types.  You use the pipe symbol (`|`) to separate the types. For example, `string | number` means a value can be either a string or a number.
