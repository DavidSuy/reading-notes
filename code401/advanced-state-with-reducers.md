# Reading: Advanced State with Reducers

## Reading

### [useReducer hook](https://reactjs.org/docs/hooks-reference.html#usereducer)

1. Name an alternative to the `useState` Hook.

   As opposed to calling useState , call useReducer with a reducer and initialState.

2. Why might the `useReducer` Hook be preferable to the `useState` Hook?

   It is preferable to useState hook when you have complex state logic or when the state of an object depends on the state of a previous one.

3. What are two ways to set the initial state?

   You can either pass in state as a second argument, or pass an init function so that you can determine the intial state outside of the reducer hook.

### [Ultimate Guide to useReducer](https://blog.logrocket.com/guide-to-react-usereducer-hook/)

1. In terms of state, what does `useReducer` expect to receive as a parameter?

   It expects to receive a reducer function and an initial state.

2. What does `useReducer` return?

   It returns an array that holds that state, and a function to later invoke that state.

3. Explain `dispatch` to a non-technical recruiter.

   The dispatcher function sends an update to state to be processed through the reducer.
