1. Why would you wrap your entire application within a context?
* So every component can have access to that context.
2. What is the purpose of a reducer?
* It determines how to update the state. It takes in the current state and an action, then determines how to modify the state based on the action.
3. What does an action contain?
* A reference to a reducer as well as stateful variables. 
4. Why do we need to copy the state in a reducer?
* Because a reducer takes in the current state and then modifies that state. So making a copy allows a way to do this cleanly.

