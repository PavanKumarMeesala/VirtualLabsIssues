# Virtual Labs Issues
Brief about the issues and bugs related to Virtual Labs developed by IIT Delhi.

## Department name: Computer Science & Engineering.   
### Module name: Data Structues - I.   
**_Major issue (may lead to misguide beginner's):_**

1. Experiment link: [Stack through Linked List](https://ds1-iiith.vlabs.ac.in/exp/stacks-queues/stacks/stack-linkedlist.html)   
Bug: We cannot perform pop operation more than one time. Although there are elements in the stack.        

- **Case 1: Stack: []**    
push(5) -> Stack[5]   
push(5) -> Stack[5, 5]   
pop() -> Stack[5]    
pop() -> Stack[]   
    
- **Case 2: Stack[]**    
push(1) -> Stack[1]    
push(2) -> Stack[2, 1]    
pop() -> Stack[1]    
pop() -> Stack[1] // Bug  

2. Experiment link: [Depth First Traversal Preorder practice in Tree Traversal](https://ds1-iiith.vlabs.ac.in/exp/tree-traversal/depth-first-traversal/dft-practice.html)  
- Bug: The pre-order traversal follows Root-Left-Right but your practice algorithm expects the Root-Right-Left.          

3. Experiment link: [Binary Search Pratice in Unsorted Arrays](https://ds1-iiith.vlabs.ac.in/exp/unsorted-arrays/binary-search/binary_search_practice.html)        
- Bug: Try to search any of the values in the array but the output remains 4, 1, 0.
  -Example:        
    - Array: 11 32 35 35 40 45 59 81 82 83        
    - Element to search: 40        
    - Correct output: 4        
    - Your expected output: 4, 1, 0. 

**_Minor issues need attention:_**        

4. Experiment link: [Preset in Stacks section](https://ds1-iiith.vlabs.ac.in/exp/stacks-queues/pretest.html)   
- Bug: Explanation is provided only for the first question.

5. Experiment link: [Infix to postfix The Whole Conversion Exercise](https://ds1-iiith.vlabs.ac.in/exp/infix-postfix/infix%20to-postfix-conversion-with-stack/infix_to_postfix.html)  
- Bug: If (input value == null) still it is pushes it into stack. Handle null value expection.    

6. Experiment link: [Breadth First Traversal Practice](https://ds1-iiith.vlabs.ac.in/exp/tree-traversal/breadth-first-traversal/bft-practice.html)        
- Bug: Almost the perfect work done!! but a subtle expection is while practicing whatever node you select any node on the last click the output will result in: Traversal Complete.Your Traversal is Correct  

- **Example:**   
 - Expected Node Sequence: 2 7 5 21 6 8 11    
 - The selected Node Sequence: 2 7 5 21 6 8 21    
 - Both resultant in: Correct        

7. Experiments links:        
[Singly Linked List Practice](https://ds1-iiith.vlabs.ac.in/exp/linked-list/singly-linked-list/sllpractice.html)  
[Singly Linked List Exercise](https://ds1-iiith.vlabs.ac.in/exp/linked-list/singly-linked-list/sllexercise.html)        
[Doubly Linked List Practice](https://ds1-iiith.vlabs.ac.in/exp/linked-list/doubly-linked-list/dllpractice.html)          
[Doubly Linked List Exercise](https://ds1-iiith.vlabs.ac.in/exp/linked-list/doubly-linked-list/dllexercise.html)        
[Circular Linked List Practice](https://ds1-iiith.vlabs.ac.in/exp/linked-list/circular-linked-list/cllpractice.html)        
[Circular Linked List Exercise](https://ds1-iiith.vlabs.ac.in/exp/linked-list/circular-linked-list/cllexercise.html)

- Bug: Same bug in all the above practice interfaces. If(input == null) still it is inserted into linked list. Handle null value exception.                 

8. Experiment link: [DFS Exercise](https://ds1-iiith.vlabs.ac.in/exp/depth-first-search/dfs/dfs-exercise.html)        
- Bug: Page is going to unresposive state with the user select nodes / performs incorrect traversal.        


