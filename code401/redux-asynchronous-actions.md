# Readings: Redux - Asynchronous Actions

## Reading

### [async actions](https://redux.js.org/advanced/asyncactions)

1. Why use Redux middleware?

   Redux middleware were designed to enable writing logic that has side effects. A Redux middleware can do anything when it sees a dispatched action: log something, modify the action, delay the action, make an async call, and more.

2. Consider the Redux Async Data Flow Diagram. Describe the flow in your own words.

- The flow starts by user triggering an event in
- the dispatch function is called, and the middleware catches the object passed to dispatch before it hits the reducers
- the middleware performs async logic and then passes that onto the reducers where the state is updated

3. How are we accommodating async in our Redux app?

   We accommodate async logic by using middleware like thunk, it is commonly used because it allows us to write functions that get dispatch and getState as arguments and then the async logic goes inside that function

### [thunk middleware](https://github.com/reduxjs/redux-thunk)

1. Why would you need `redux-thunk` middleware?

   Thunk middleware for Redux. It allows writing functions with logic inside that can interact with a Redux store's dispatch and getState methods.

2. Redux Thunk middleware allows you to write action creators that return a \_\_\_\_ instead of an action.

   It allows you to write action creators that return a function rather than an action.

3. Describe how any return value from the inner thunk function will be made available.

   any return value from the inner function will be available as the return value of dispatch itself
