Socket IO

**What does it mean that web sockets are bidirectional? Why is this useful?**

- Web sockets are bidrectional, which means information can travel in both directions, making it easy for various applications to work seamlessly together.

**Does socket.io use HTTP? Why?**

- Socket.io does use HTTP since it was developed for the purpose of developing web applications. 

**What happens when a client emits an event? What happens when a server emits an event?**

- When a client emits an event it sends the payload to the server and runs the function that was set as its call back. When the server emits it can send a payload to multiple clients. 
