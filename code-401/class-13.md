Readings: Message Queues
========================

Reading
-------

[Socket.io Chat Example](https://socket.io/get-started/chat/)

1. Explain to a non-technical recruiter what the Chat Example (above) does.
    > sockets are bi-directional communication channels, which are faster and more reliable because the server "pushes" the messages to clients. It works how we've become familiar with IMs.
2. What proof of life are we getting on the backend from the above app?
    > `user connected`
3. Socket.IO gives us the io.emit() method to send an event to everyone. What flag would you use if you want to send a message to everyone except for a certain emitting socket?
    > sends the message to everyone. To send it to only specific people use the `broadcast` flag

[Rooms](https://socket.io/docs/v4/rooms)

1. What is a room and how might a room be useful?
    > a channel that sockets can join and leave; used to broadcast to a subset of users.
2. How do you join a room?
    > subscribe the socket to a given channel with `join` and use `to` or `in` method and emit some event
3. how do you leave a room?
    > call `leave` like you would for `join`

[Namespaces](https://socket.io/docs/v4/namespaces/)

1. What is a Namespace and what does it allow you to do?
    > a comms channel that splits the logic of an app over a single connection.
2. Each namespace potentially has its own what? (hint: 3 things)
    * event handlers
    * rooms
    * middleware
3. Discuss a possible use case for separate namespaces
    > if you need a room with special authorization, like an or manager admin room

Bookmark and Review
-------------------

[Socket.io Emit Cheatsheet](https://socket.io/docs/v4/emit-cheatsheet/)
