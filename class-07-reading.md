
1. What code does the server actually run?
- The server runs the code you tell it to? I'm not sure how to answer this question. Or did you mean how long does the server run that code? It is supposed to run it until told otherwise, I think?
2. What Express/HTTP operations map to CRUD operations?
- Get, Post, Put, Delete => Read, Create, Update, Delete
3. What does res.send() do?
- Sends the response object data back to the client in the properly formatted way.
4. What is the order of operations for the three categories of middleware (handler, application, route)?
- Application, Route, Handler.
5. What is the parameter next used for?
- In the context of middleware, next is used to call the next middleware in the chain.
