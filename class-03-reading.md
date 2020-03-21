

1. Why would a developer choose to make data models?
- In order to create a standardized way to store large amounts of data formatted in uncertain ways.
2. What purpose do CRUD operations serve?
- Create, Read, Update, Delete. These special functions place the actions onto rails so that they have to follow the defined structure of the data model.
3. What kind of database is Postgres? What kind of database is MongoDB?
- Postgres is a SQL database. Mongo is a NoSQL database.
4. What is Mongoose and why do we need it?
- Mongoose is the package that MongoDB uses. It is the delivery method between our application and our database. Our application speaks to Mongoose in JavaScript and Mongoose translates that into stuff MongoDB can work with. 
5. Define three related pieces of data in a possible application. An example for a store application might be Product, Category and Department. Describe the contraints and rules on each piece of data and how you would relate these pieces to each other. For example, each Product has a Category and belongs in a Department.
- For an apparel brand: Clothing, Accessories, and Hats. Clothing would be in a separate data pool than the other two. Accessories would be adjacent to Clothing. And Hats would fall under Accessories. Perhaps Accessories could fall under Clothing as well but in my head, they are different enough that they should be separate categories of item.
