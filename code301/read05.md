# Reading

## React Docs - Thinking in React

1. What is the single responsibility principle and how does it apply to components?
  Single responsibility principle is the principle that a component should ideally only do one thing and you should split it up when it grow beyond that.

2. What does it mean to build a 'static' version of your application?
  Building a static version of your application means to build a version that have no interactivity first because in doesn't require much thinking, but a lot of type as a trade off.

3. Once you have a static application, what do you need to add?
  Once you have a static application, you will then add the interactivity.

4. What are the three questions you can ask to determine if something is state?

- Is it passed in from a parent via props? If so, it probably isn't state.
- Does it remain unchanged over time? If so, it probably isn't state.
- Can you compute it based on any other state or props in your componont? If so, it isn't state.

5. How can you identify where state needs to live?

- Identify every component that renders something based on that state.
- Find a common owner component (a single component above all the components that need the state in the hierarchy).
- Either the common owner or another component higher up in the hierarchy should own the state.
- If you can’t find a component where it makes sense to own the state, create a new component solely for holding the state and add it somewhere in the hierarchy above the common owner component.

------

## Higher-Order Functions

1. What is a "higher-order function"?
  Higher-oder functions are functions that operate on other functions, either by taking them as arguments or by returning them.

2. Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?

    > function greaterThan(n) {
    >
    > return m => m > n;
    >
    > }
    >
    > let greaterThan10 = greaterThan(10);
    >
    > console.log(greaterThan10(11));
    >
    > // → true

      Line 2 of this function is callback function that is returning a number if it is greater than than the argument n.

3. Explain how either map or reduce operates, with regards to higher-order functions.
  The map higher-order function operates by taking in a callback function and returning another array after iterating through the array it was called and doing something base on the callback.
