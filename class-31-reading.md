# Redux - Combined Reducers

## Vocab

* Combined Reducers
  - pulling in more than one reducer from a source and creating a keyed object from them.
  - kind of like having multiple properties in a state object? Except that object has a function as its value.
  
* `combineReducers()` 
  - built in Redux method that you import
  - this helper function can help merge multiple reducers into a single reducing function you can pass to your store.
  - the result reducer will call every child reducer and gather their results into a single state object.
 
* Single Responsibility Principle
  - each reducer should only have a single part of state to manage
  
## ProTips

* You can have multiple reducers respond to the same action type
  - This can create an event where lots of things change at once, kinda slick



