# Reading

## React Docs – lists and keys

1.What does .map() return?
.map() returns an array.

2.If I want to loop through an array and display each value in JSX, how do I do that in React?
You will have the put the new looped array of JSX element in a curly braces in the render function.

3.Each list item needs a unique key
4.What is the purpose of a key?
Keys help React identify which items have changed, are added, or are removed.

## The Spread Operator

1.What is the spread operator?
The spread operator is syntax for adding items to array, combining array or objects, and spreading an array out into a function’s arguments.

2.List 4 things that the spread operator can do.

- Add items to arrays
- Combine arrays
- Combine objects
- Spreading an array out into a function’s arguments

3.Give an example of using the spread operator to combine two arrays.
Let arr1 = [1,2,3]
Let arr2 = [4,5,6]
Let arr3 = […arr1, …arr2] // [1,2,3,4,5,6]

4.Give an example of using the spread operator to add a new item to an array.
Let arr1 = [1,2,3]
Let arr2 = […arr1, 4, 5, 6]

5.Give an example of using the spread operator to combine two object into one.
Let firstName = {firstName: ‘David’}
Let lastName = {lastName: ‘Suy’}
Let fullName = {…firstName, … lastName} // {firstName: ‘David’, lastName: ‘Suy’}

# Videos

## How to pass Functions between Components

1. In the video, what is the first step that the developer does to pass functions between components?
Create a function in the parent and pass it down to the children with props.
2. In your own words, what does the increment function do?
The increment function in the person call the increment function from the parent to change the state in the parent and change the count.
3. How can you pass a method from a parent component into a child component?
You can pass a method from a parent component into a child component by passing it through props.
4. How does the child component invoke a method that was passed to it from a parent component?
The child component invokes the method that was passed to it from the parent by calling if from the props.
