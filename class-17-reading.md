
1. What do the layers in the OSI and TCP/IP models represent?
- The layers represent the different steps needed to get data from one place to another securely.
2. What is the benefit of transforming data into packets? 
- Packeted data is harder to intercept and read. Packeted data is easier to send and receive. 
3. UDP is often referrered to as a connectionless protocol. Why is this?
- UDP doesn't establish a strong security connection and as such is less safe. UDP also doesn't maintain a continuous connection throughout the data send. 
4. Can a socket server application have multiple socket connections? Can a socket connection application be connected to multiple socket servers? Can an application be both a socket server and a socket connection?
- A socket server can have multiple socket connections. Based on the code, it doesn't look like a connection can be connected to multiple servers. And I guess an app could be both a server and a connection. But it probably can't be a connection to its own server...?
