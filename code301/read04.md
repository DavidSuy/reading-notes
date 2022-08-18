# Reading

## React - Forms

1. What is a 'controlled Component'?
    A controlled Component is an input form element whose value is controlled by the React component that renders the form and also control what happens in that form on subsequent user input.

2. Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why?
    We should update the stae with their responses as soon as they enter them because you can pass the value to UI elements or reset it from other event handlers.

3. How do we target what the user is entering if we have an event handler on a input field?
    We target what the user is entering if we have an event handler on a input field by accessing the event.target.value

## The Conditional (Ternary) Operator Explained

1. Why would we use a ternary operator?
    We use ternary operaters to shorten our *if* statement into one line of code.

2. Rewrite the following statement using a ternary statement:
    >if(x===y){
    >
    >  console.log(true);
    >
    >} else {
    >
    >  console.log(false);
    >
    >}

        x===y ? console.log(true) : console.log(false)