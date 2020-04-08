1. What is a benefit to using express.Router()?
- It allows us to further modularize our route handling.
2. When I say that top-down order matters in Express, what does that mean?
- It means that even though app middleware is typically meant to be run before handler middleware, you can change this by moving an app middleware assignment after a handler middleware assignment.
3. Why do we use a model class (with create(), read(), etc.) instead of directly calling MongoDB operations (such as save(), find(), etc.) within our Express route handlers?
- I'm not entirely sure, but it seems like it would be useful to implement a model class so that you can better stick to a schema and also call other middleware methods before finally calling on MongoDB operations?
