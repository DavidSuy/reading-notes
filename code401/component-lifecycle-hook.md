# Reading: Component Lifecycle / `useEffect` Hook

## Reading

### [effects hook](https://reactjs.org/docs/hooks-effect.html)

1. What purpose does `useEffect` serve in a function component compared to its counterpart(s) in class components?

   UseEffect hook performs the same functions that would normally be performed by the componenetDidMount, componentDidUpdate, and componentWillUnmount methods.

2. When using the useEffect Hook:

   1. What does `useEffect` do?

      Tell React that your component needs to do something after render.

   2. Why is `useEffect` called inside a component?

      It allows us to access the count state variable from the effect.

3. Explain the importance of properly implementing effects with Cleanup

   You need to use cleanup after the useEffect hook to prevent a memory leak from occurring.
