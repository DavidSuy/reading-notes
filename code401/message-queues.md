# Readings: Message Queues

## Reading

### [Socket.io Chat Example](https://socket.io/get-started/chat/)

1.  Explain to a non-technical recruiter what the Chat Example (above) does.
    What is Socket.IO chat?

    A basic chat application, it involves polling the server for changes, keeping track of timestamps, and it’s a lot slower than it should be.

2.  What proof of life are we getting on the backend from the above app?
    If you open your network tab in your developer tools, you should see a few HTTP requests:

         http://localhost:3000

3.  Socket.IO gives us the io.emit() method to send an event to everyone. What flag would you use if you want to send a message to everyone except for a certain emitting socket?

        socket.broadcast.emit('')

### [Rooms](https://socket.io/docs/v4/rooms)

1. What is a room and how might a room be useful?

   A room is an arbitrary channel that sockets can join and leave. It can be used to broadcast events to a subset of clients.

2. How do you join a room?

```js
io.on('connection', (socket) => {
  socket.join('some room');
});
```

3. How do you leave a room?

```js
io.on('connection', (socket) => {
  socket.leave('some room');
});
```

### [Namespaces](https://socket.io/docs/v4/namespaces/)

1. What is a Namespace and what does it allow you to do?

   A Namespace is a communication channel that allows you to split the logic of your application over a single shared connection (also called "multiplexing").

2. Each namespace potentially has its own what? (hint: 3 things)

   - Event handlers
   - Rooms
   - Middlewares

3. Discuss a possible use case for separate namespaces

   You want to create a special namespace that only authorized users have access to, so the logic related to those users is separated from the rest of the application.

## Bookmark and Review

[Socket.io Emit Cheatsheet](https://socket.io/docs/v4/emit-cheatsheet/)
