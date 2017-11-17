## Answers
1. What are the order of insertions/removals for the following data structures?
   - Stack - Last in, first out. Stacks rely on using push and pop for retrieval; Push stores something on the top of the stack and Pop retrieves something from the top of the stack. If items 1, 2, and 3 were pushed onto the stack, item 3 will be popped off first as it was last to be pushed on.
   - Queue - First in, first out. Essentially the reverse of Stack insertion - rather tahn retrieving the most recently added item, we are instead taking the item least recently added. These retrievals are done using enqueue and dequeue rather than push and pop.
2. What is the retreival time complexity for the following data structures?
   - Linked List - O(1) for insertion, O(N) for lookups;Will always execute within same time frame regardless of size due to the way in which it is set up.
   - Hash Table - inserts and lookups are O(1) on average; Worst-case performance, in that the performance will grow linearly and in direct proportion to the size of the data set.
   - Binary Search Trees - O(logN); Since these searches generally have multiple choices but only one will need to be chosen.
3. What are some advantages to using a Hash Tables over an array in JavaScript?
   - From a purely performant perspective, Hash Tables are more efficient in both finding and retrieving values. Since most likely you will not know in what index position the value is located within an array, you would then have to scan through the entire index.