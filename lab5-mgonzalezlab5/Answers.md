1) Why does LinkedStack not require an explicit constructor?
  - Because it calls the Node<E> class which has a constructor
2) What is the time and (extra) space complexity of each of the LinkedStack methods, as well as ReverseLines.main?
  - push
    - Time: O(1)
    - Space: O(1)
  - peek 
    - Time : O(1)
    - Space: O(1)
  - pop
    - Time: O(1)
    - Space: O(1)
  - isEmpty
    - Time: O(1)
    - Space: O(1)
  - asList
    - Time: O(n)
    - Space: O(n)
  - ReverseLines.main 
    - Time: O(n)
    - Space: O(n)
3) How else (not using Node) could we have implemented LinkedStack in such a way that it is still based on a linked list but the asList method uses constant time and space? 
  - We could've implemented LinkedStack using a LinkedList becasue it allows for constant time insertions and removals
4) Is it better for push and pop to return the item or the stack itself? Briefly discuss the pros and cons of each design.
  - Better to return item 
  
  * Item:
    - Pros: 
      - Takes less time to return 1 item and it's more clear what was added or removed.
    - Cons:
      - Only get 1 item at a time. Can't see everything at once.
  
  * Stack:
    - Pros:
      - Can see everything at once
    - Cons:
      - Takes more time to return all items at once
