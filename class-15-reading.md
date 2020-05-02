
1. What is a leaf node? Why is it important to be able to find leaf nodes?
- A leaf node is a node without any edges or connections. I assume these are important because they define the ends of the tree?
2. Describe the differences between pre-order, in-order, and post-order traversal. Why are they called pre, in, and post order? 
- Preorder: `root >> left >> right`
- In-order: `left >> root >> right`
- Post-order: `left >> right >> root`
- I really am not sure why they are named they way they are. But I'm sure we will find out soon!
3.What is the height of a fully balanced (each non-leaf node has two children) tree? What is this used for?
- Log n where n is the number of nodes. This is used for modeling on a binary search tree. Which, from what I gather, is like a tricky way of searching through a tree a bit faster than you would normally be able to. This helps you avoid having to check every single node I think?
4. How are stacks and queues used in relation to trees?
- Preorder/depth first traversal of the tree operates in a call stack. In-order/breadth first traversal works in a queue.
