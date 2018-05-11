For each of the methods associated with each data structure, classify it based on its runtime, using Big O notation.

## Linked List

1. What is the runtime complexity of `addToTail`?
  
    a. What if our list implementation didn't have a reference to the tail of the list in its constructor? What would be the runtime of the `addToTail` method?

2. What is the runtime complexity of `removeHead`?

3. What is the runtime complexity of `contains`?

4. What is the runtime complexity of `getMax`?

### Linked List Answers
1. O(1)
1. (a) ?
2. O(1)
3. O(n)
4. O(n)


## Queue

1. What is the runtime complexity of `enqueue`?

2. What is the runtime complexity of `dequeue`?

3. What is the runtime complexity of `isEmpty`?

4. What is the runtime complexity of `length`?

### Queue Answers
1. O(1)
2. O(1)
3. O(1)
4. O(1)


## Doubly Linked List

1. What is the runtime complexity of `ListNode.insertAfter`?

2. What is the runtime complexity of `ListNode.insertBefore`?

3. What is the runtime complexity of `ListNode.delete`?

4. What is the runtime complexity of `DoublyLinkedList.addToHead`?

5. What is the runtime complexity of `DoublyLinkedList.removeFromHead`?

6. What is the runtime complexity of `DoublyLinkedList.addToTail`?

7. What is the runtime complexity of `DoublyLinkedList.removeFromTail`?

8. What is the runtime complexity of `DoublyLinkedList.moveToFront`?

9. What is the runtime complexity of `DoublyLinkedList.moveToBack`?

10. What is the runtime complexity of `DoublyLinkedList.delete`?

    a. Compare the runtime of the doubly linked list's `delete` method with the worst-case runtime of the `Array.splice` method. Which method generally performs better?

### Doubly Linked List Answers
1. O(1)
2. O(1)
3. O(1)
4. O(1)
5. O(1)
6. O(1)
7. O(1)
8. O(1)
9. O(1)
10. O(1)
10.a. They both perform O(1). I think the Array.splice method would perform better for larger deletions.

## Binary Search Tree

1. What is the runtime complexity of `insert`? 

2. What is the runtime complexity of `contains`?

3. What is the runtime complexity of `getMax`? 

4. What is the runtime complexity of `depthFirstForEach`?

5. What is the runtime complexity of `breadthFirstForEach`?

6. [Stretch Question] What is the runtime complexity of your `checkBalanced` function?

### Binary Search Tree Answers
1. O(log n)
2. O(log n)
3. O(n log n)
4. O(n)
5. O(n)

## Heap

1. What is the runtime complexity of your `heapsort` function?

2. What is the space complexity of the `heapsort` function? Recall that your implementation should return a new array with the sorted data. What would be the space complexity if your function instead altered the input array?

3. What is the runtime complexity of `bubbleUp`?

4. What is the runtime complexity of `siftDown`?

5. What is the runtime complexity of `insert`?

6. What is the runtime complexity of `delete`?

7. What is the runtime complexity of `getMax`?

### Heap Answers
1. O(n log n)ß
2. O(1)
3. O(n)
4. O(n)
5. O(log n)
6. O(log n)
7. O(1)
