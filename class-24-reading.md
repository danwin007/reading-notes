1. Why do we not need more .html pages in a multi-page React app?
- Because the multi-page app simply reloads the existing page with new components? As opposed to making entirely new pages?
2. If we wanted a component to show up on every page, where would we put it and why?
  * Outside the `<BrowserRouter/>`
  * Inside the `<BrowserRouter />`, outside a `<Route />` 
  - I am guessing this one. It seems like the `<BrowserRouter />` populates to every page whereas the `<Route />` only populates components to specific pages?
  * Inside a `<Route />`
3. What does props.children contain?
- I'll be honest. I read the reading example a few times and I still do not know. I read one of the accompanying articles and it is still fuzzy. Best I can tell, props.children is a way of passing parts of a component around?
