
1. Given the examples of front-end events such as button click, window resize, form submit, etc, what are some examples of back-end events?
- Enqueue, dequeue, add, delete, find.
2. Why are events sometimes better than asynchronous actions with callbacks?
- Because they can be queued up such that they process in a specific order? Rather than have them process whenever the callback finishes? This allows you to handle data in a predictable way.
3. What does an EventEmitter instance do?
- It allows us to raise new events and listen to events that have been raised. It's like an event handler?
4.When is a program’s call stack, event queue, and event loop active?
- The call stack is always active. The event queue is active when async or callback items are active. The event loop is a continually running process that checks to see if the call stack is empty.
