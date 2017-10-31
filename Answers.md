1. What is the purpose of the various auxiliary methods `populateList`, `populateFifoList`, and `ReverseLines.printReverse`?
    - To add items to a list and to print them out through recursion instead of having to iterate through a loop. 
2. Why do these methods need to have arguments, and how does the argument change from one recursive call to the next?
    - These methods need arguments so that they can call themselves and thus continue solving the rest of the problem until a base case is reached. The argument changes from one node to the next or from one input to the next.
3. What are the time and space complexity of each of the `populateList` `populateFifoList` methods, as well as `ReverseLines.printReverse`?
    - `populateList` 
      - Time = O(N)
      - Space = O(N)
    - `populateFifoList`
      - Time = O(N)
      - Space = O(N)
    - `ReverseLines.printReverse`
      - Time = O(N)
      - Space = O(N)
4. Which of these methods can be implemented using `while` loops?
    - All of these methods can be implemented using `while` loops
