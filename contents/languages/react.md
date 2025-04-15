# React.js Interview Questions and Answers

**1. What is JSX?**

**Answer:** JSX (JavaScript XML) is a syntax extension to JavaScript that allows you to write HTML-like structures within your JavaScript code. It gets transformed into regular JavaScript function calls that create DOM elements.

**2. What are React components? Differentiate between functional and class components.**

**Answer:** React components are the building blocks of a React application's UI. They are reusable pieces of code that manage their own data and rendering.

* **Functional Components:** - Are simple JavaScript functions that accept props as arguments and return JSX. They are generally stateless and used for simpler UI parts.
* **Class Components:** - Are ES6 classes that extend `React.Component`. They can have state, lifecycle methods, and are typically used for more complex UI logic.

**3. What is state in React? How is it different from props?**

**State** is a plain JavaScript object that is local to a component and holds data that can change over time. When the state of a component changes, React re-renders the component.

**Props** (short for properties) are read-only values passed down from a parent component to a child component. Child components cannot directly modify the props they receive.

**4. What are React Hooks?**

**Answer:** React Hooks are functions that let you "hook into" React state and lifecycle features from functional components.  They were introduced in React 16.8 and solve the problems of using class components for state management and side effects.

**5.  Explain the Virtual DOM.**

**Answer:** The Virtual DOM (Document Object Model) is a lightweight JavaScript object which resides in memory.  It acts as a representation of the actual DOM.  When state changes in a React component, React first updates the Virtual DOM.  Then, React compares the Virtual DOM to the previous version of the Virtual DOM.  React then updates only the changed elements in the real DOM.  This process is called reconciliation.

**6. What is the purpose of `useEffect`?**

**Answer:** The `useEffect` Hook lets you perform side effects in functional components.  Side effects could be fetching data, updating the DOM directly, setting up subscriptions, and cleaning up those subscriptions.
