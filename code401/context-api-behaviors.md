# Reading: Context API - Behaviors

## Reading

### [Hooks and Context example](https://medium.com/swlh/snackbars-in-react-an-exercise-in-hooks-and-context-299b43fd2a2b)

1. With regard to the React Context API, what does a “provider” do?

   The provider gives global access to the state it is currently providing.

2. With regard to the React Context API, how would we implement a “consumer” role?

   Import it into our component and then use the use context hook from react to act as a consumer.

3. Specifically with Context, how are we “wrapping” components to achieve our goals?
   How do you wrap a component?

Our child components are wrapped in the context to provide globally accessible state.

### [Awesome React Context links](https://github.com/diegohaz/awesome-react-context)

1. Consume content from (at least) two more of the Awesome React Context links. After some familiarity with React Context, once again share your takeaways from each:
   1. Takeaway 1: You could actually use a regular JavaScript module to avoid these problems. Just put the data in a singleton module and poof, it's accessible/importable anywhere.
   2. Takeaway 2: this is where state management libraries like redux come into play (specifically react-redux). They allow you to get data from the store easily anywhere in the tree.
