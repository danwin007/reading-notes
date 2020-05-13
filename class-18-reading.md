
1. What does it mean that web sockets are bidirectional? Why is this useful?
- This means that data can transfer back and forth, two-way data! This allows for more elegant implementation.
2. Does socket.io use HTTP? Why?
- It does use HTTP. It also uses TCP. The TCP layer is for data transfer. The HTTP layer is to ensure the connection between client/server is kept active and authenticated.
3. What happens when a client emits an event? What happens when a server emits an event?
- I am not entirely sure of the difference. As the connection is two way, I assume the client emits events that only the server can listen to? Whereas the server emits events that all clients can listen to? Not sure about that though. 
