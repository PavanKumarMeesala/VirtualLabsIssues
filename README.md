# Virtual Labs Issues
Brief about the issues and bugs related to Virtual Labs developed by IIT Delhi.

## Department name: Computer Science & Engineering.   
### Module name: Data Structues - I.   

Experiment link: [Preset in Stacks section](https://ds1-iiith.vlabs.ac.in/exp/stacks-queues/pretest.html)   
Bug: Explanation is provided only for the first question only.

Experiment link: [Stack through Linked List](https://ds1-iiith.vlabs.ac.in/exp/stacks-queues/stacks/stack-linkedlist.html)   
Bug: We cannot perform pop operation more than one time.    
**Case 1: Stack: []**    
push(5) -> Stack[5]   
push(5) -> Stack[5, 5]   
pop() -> Stack[5]    
pop() -> Stack[]   
    
**Case 2: Stack[]**    
push(1) -> Stack[1]    
push(2) -> Stack[2, 1]    
pop() -> Stack[1]    
pop() -> Stack[1] // Bug  

Experiment link: [Infix to postfix The Whole Conversion Exercise](https://ds1-iiith.vlabs.ac.in/exp/infix-postfix/infix%20to-postfix-conversion-with-stack/infix_to_postfix.html)  
Bug: If (input value == null) still it is pushes it into stack. Handle null value expection.    

Experiment link: [Depth First Traversal Preorder practice in Tree Traversal](https://ds1-iiith.vlabs.ac.in/exp/tree-traversal/depth-first-traversal/dft-practice.html)  
Bug: The pre-order traversal follows Root-Left-Right but your practice algorithm expects the Root-Right-Left.  

Experiment link: [Breadth First Traversal Practice](https://ds1-iiith.vlabs.ac.in/exp/tree-traversal/breadth-first-traversal/bft-practice.html)
Bug: Almost the perfect work done!! but a subtle expection is while practicing whatever node you select on the last click the output will result in: Traversal Complete.Your Traversal is Correct  

**Example:**   
Expected Node Sequence: 2 7 5 21 6 8 11    
The selected Node Sequence: 2 7 5 21 6 8 21    
            

