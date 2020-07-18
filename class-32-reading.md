This was a short piece of reading. 

Normally, action generators return a function that holds an action object. However, sometimes you want to do something before you send that action. In this case, sometimes you want to fetch something from a report API.

In that event, you will need to arrange your action generator such that it returns a function, not an action object. To do this, we use a middleware called "thunk". This middleware screens every dispatched action. If the action object is standard, then it lets it process. If the action returns a function, then `thunk` processes that function and dispatches what the function returns, since Redux expects and requires dispatched actions to be sent as objects?


