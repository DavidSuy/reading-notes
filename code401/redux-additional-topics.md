# Readings: Redux - Additional Topics

## Reading

### [Redux Toolkit (RTK)](https://redux-toolkit.js.org/introduction/getting-started)

1. What concerns are addressed by Redux Toolkit?

   - "Configuring a Redux store is too complicated"
   - "I have to add a lot of packages to get Redux to do anything useful"
   - "Redux requires too much boilerplate code"

2. What does `configureStore()` do?

   A friendly abstraction over the standard Redux createStore function that adds good defaults to the store setup for a better development experience.

3. How would I use `createSlice()`?

   A function that accepts an initial state, an object of reducer functions, and a "slice name", and automatically generates action creators and action types that correspond to the reducers and state.

### [MobX](https://mobx.js.org/getting-started.html)

1. What is Mobx?

   MobX is a simple, scalable and battle tested state management solution.

2. How does MobX make it “impossible” to produce an inconsistent state?

   Data needs to be normalized, referential integrity can no longer be guaranteed and it becomes next to impossible to use powerful concepts like classes in case you fancy those.

3. How would we build a reactive user interface?

   Mobx will automatically execute cde that depends solely on state, by introducing the observable annotations.

-

## Tutorial

### [Tutorial](https://redux-toolkit.js.org/tutorials/intermediate-tutorial)

1. What take-away(s) did this tutorial provide?

   This tutorial gave be the basic use of the redux toolkit and react-redux together

## Bookmark and Review

[Redux Toolkit (RTK)](https://redux-toolkit.js.org/)

[HookState](https://hookstate.js.org/)
