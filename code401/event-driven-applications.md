# Readings: Event Driven Applications

## Reading

### [Event Driven Programming](https://www.digitalocean.com/community/tutorials/nodejs-event-driven-programming)

1. What native Node.js module allows us to get started with Event Driven Programming?

   Event-Driven Programming is a logical pattern that we can choose to confine our programming within to avoid issues of complexity and collision.

2. What is the value of Object Oriented Programming used in tandem with Event Driven Programming?

   By registering event listeners we can actually reverse the flow of communication between our objects. Rather than on object needing to reach inside another object to trigger a function, our objects can just emit events and whichever objects are listening to those event will process it in the way they have been told to. The source of an objects behavior is now entirely contained within itself, rather than needing to be accessed by external objects.

3. Consider your knowledge of Event Driven Programming in the Web Browser, now explain to a non-technical friend how Event Driven Programming might be useful on the backend using Node.js.

   Event driven programming in the backend using Node.js is useful. Every time you interact with a webpage through it’s user interface, an event is happening. When you click a button a click event is triggered. When you press a key a keydown event is triggered. These events have associated functions that, when triggered, are executed to make a change to the user interface in some way.

## Bookmark and Review

[Node docs: events](https://nodejs.org/api/events.html)
