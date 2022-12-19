# Readings: Redux - Combined Reducers

## Reading

### [Multiple Reducers Example](https://www.youtube.com/watch?v=gBER4Or86hE)

1. Why create multiple reducers?

   Having one large reducer function that changes many different parts of the state would be hard to debug and maintain

2. How would you combine multiple reducers?

   You combine multiple reducers by using the combine reducers function from redux.

3. How will you manage state as an immutable object? why?

   When we use redux, we will not mutate state, instead we will replace it with a reducer function. This makes the process have some very desirable properties.

### [Redux Docs: Using Combined Reducers](https://redux.js.org/recipes/structuring-reducers/using-combinereducers/)

1. `combineReducers` is a utility function to simplify the most common use case when writing **\_\_**\_ **\_\_**\_\_\_ .

   Redux reducers

2. Explain how `combineReducers` assembles the new state tree.

   It creates a new state with the same keys as the initial state.

3. How would you define initial state in an app using `combineReducers`?

   InitialState is returned when the reducer does gets undefined as the previous state.

### [Redux Docs: Combined Reducer Syntax](https://redux.js.org/api/combinereducers/)

1. Why will you want to split your reducing functions as your app becomes more complex?

   In order to fulfill the principle of single purpose, we can split reducers so that each does one "thing".

2. The **\_** helper function turns an object whose values are different reducing functions into a single reducing function you can pass to \_\_\_

   The combinerReducer function turns objects into a singler reducing function that can be passed to createStore.

3. What is a popular convention when naming reducers?

   Naming them after the slice of state that they manage is a common naming convention.
