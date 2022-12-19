# Reading: `useState()` Hook

## Reading

### [Introducing Hooks](https://reactjs.org/docs/hooks-intro.html#motivation)

1. What was the motivation for introducing Hooks?

   Hooks solve a wide variety of seemingly unconnected problems in React that we’ve encountered over years.

2. What changes are important regarding implementing Hooks versus Component Classes?

   Hooks allow you to use Reacts features without classes.

3. Hooks allow you to reuse stateful logic without changing **\_\_\*\***\_ \_\_\*\*\_\_\_\_\_.

Hooks allow you to reuse stateful logic without changing your component hierarchy.

### [hooks api](https://reactjs.org/docs/hooks-overview.html)

1. Name two rules imposed by React Hook usage.

   - Don't call Hooks inside loops, conditions, or nested functions. ...
   - Don't call Hooks from regular JavaScript functions. ...
   - You can skip to the next page explaining how to write your own Hooks now. ...
   - This is why Hooks must be called on the top level of our components.

2. How would you identify a custom Hook and why might you create one?

   If the name starts with use and calls other hooks it is considered a custom hook.

### [the state hook](https://reactjs.org/docs/hooks-state.htm)

1. What is a Hook?

   Hooks are a means to reuse stateful logic, and hook into React features

2. When would I use the `useState` Hook?

   When you write a functional component and need state for that component.

3. If you were to add React state to a function component by declaring a state variable:

   1. What does calling `useState` do?

      It declares a state variable so that a value can be preserved.

   2. What do we pass to `useState` as an argument?

      We pass an intial state to the usestate hook.

   3. What does `useState` return?

      Use state returns a pair of values. One for referencing the state, and another for setting the state.

## Bookmark and Review

[hooks api reference](https://reactjs.org/docs/hooks-reference.html)
