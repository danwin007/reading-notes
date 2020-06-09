1. Describe a case where snapshot testing would be useful, and describe another case where it would be ineffective.
- A snapshot test is useful for a fully developed UI page that you want to ensure does not change throughout development. Snapshot testing is less useful if you are constantly changing the design of your UI.
2. What is the difference between full mount and shallow mount?
- Full mounting allows you render the entire component as well as any children components. Shallow mounting minimizes the render of any imported components, and instead focuses on fully rendering the current component only.
3. What does npm run build do?
- The `npm run build` command creates a "build" of your application. It takes all your similar file types (CSS, JS) and smooshes all the modularized files into a single file of the appropriate type. This helps minimize load times for sites that expect to scale up for large userbases.
 
