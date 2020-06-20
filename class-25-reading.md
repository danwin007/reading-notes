1. Is a HashTable useful for search or sorting operations? Why?
- Kind of. It seems like it is more useful for storing data and quickly retrieving that data. So...a search! Proper use of the hash table should let you retrieve data in O(1) time.
2. What makes a good hash function?
- A good hash function should be deterministic: the output should be determined only by the input. No randomness.
3. Why should you try to reduce the number of collisions?
- Collisions increase the chance of losing keys via overwriting data. 
4. What is stored at each index of a HashTable? Why?
- The entire key/value pair is stored at each index. This is because different keys can lead to the same index. That way we know which value to retrieve when a certain key leads to an index. 
