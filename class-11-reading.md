
1. Come up with an application scenario where you would want to use a stack.
- This one I can't quite think of. All the practical app scenarios I can come up with would better fit the queue model, as you usually want to services requests by the order they came in. Regarding stack, the only thing I can think of is how the code is processed, where operations are "stacked" on top of each other. I do not know how that would apply to building apps. At least customer facing apps.
2. Come up with an application scenario where you would want to use a queue.
- Maybe a food ordering app? Because you want to take care of orders as they come in, so the first in line should be the first serviced.
3. Why are pop, push, enqueue and dequeue always O(1)?
- It takes the same amount of time no matter how many nodes you have in the stack or queue.
4. Why do stacks and queues not have traversal or searching operations?
- I have no idea. But they seem similar to linked lists in that you are only really interacting with certain parts of the data structure. And you have to make your own functions to do tricky things in order to move nodes around. You do not get fancy operations like with arrays. 
