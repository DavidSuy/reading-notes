# Reading: Application State with Redux

## Reading

### [Dan Abramov Redux Tutorials](https://egghead.io/courses/getting-started-with-redux)

1. What is the first principle of Redux?

   Represent the whole state of your application in a single javascript object

2. What is a store and what do we use our reducers for within that store?

   The Redux store brings together the state, actions, and reducers that make up your app.
   Store. A store holds the whole state tree of your application. The only way to change the state inside it is to dispatch an action on it.

3. Name three Redux store methods given to us by createStore and describe their use.

- reducer (Function): A reducing function that returns the next state tree, given the current state tree and an action to handle.

- [preloadedState] (any): The initial state. You may optionally specify it to hydrate the state from the server in universal apps, or to restore a previously serialized user session. If you produced reducer with combineReducers, this must be a plain object with the same shape as the keys passed to it. Otherwise, you are free to pass anything that your reducer can understand.

- [enhancer] (Function): The store enhancer. You may optionally specify it to enhance the store with third-party capabilities such as middleware, time travel, persistence, etc. The only store enhancer that ships with Redux is applyMiddleware().

4. Explain to a non-technical recruiter what `combineReducers()` does and why it is useful.

   The combineReducers helper function turns an object whose values are different reducing functions into a single reducing function

## Bookmark and Review

[worlds easiest guide to redux](https://medium.freecodecamp.org/understanding-redux-the-worlds-easiest-guide-to-beginning-redux-c695f45546f6)

[testing reducers](https://medium.com/@netxm/testing-redux-reducers-with-jest-6653abbfe3e1)

[Redux Docs](https://redux.js.org/)
