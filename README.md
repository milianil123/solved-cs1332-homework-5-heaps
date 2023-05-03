Download Link: https://assignmentchef.com/product/solved-cs1332-homework-5-heaps
<br>
For this assignment, you will be coding a max heap that is backed by an array. A max heap is a type of binary tree with two main properties.

<ul>

 <li><strong>Shape Property</strong>: The tree must be complete, meaning that all levels of the tree must be full except the bottommost level, which if not full must be filled from left to right.</li>

 <li><strong>Order Property</strong>: Each node’s data is larger than the data in its two children. There is no explicit relationship between sibling nodes.</li>

</ul>

These properties imply that the largest element in the heap will be at the root of the heap.

Although heaps are usually classified as a type of tree, they are commonly implemented using an array due to their completeness. In your implementation, you should <strong>leave index 0 empty and begin your heap at index 1</strong>. There are two constructors that are provided to you. One initializes the heap to a capacity specified as a constant in MaxHeap.java. The other constructor should implement the BuildHeap algorithm that was taught in lecture, which is an algorithm that creates a heap in <em>O</em>(<em>n</em>) time. <strong>Simply adding the elements one by one will not receive credit </strong>since it would be <em>O</em>(<em>n</em>log(<em>n</em>)) in the worst case; see the javadocs for this constructor for more specifications.

<strong>You may assume that your implementation does not need to handle duplicate elements</strong>. That is, the add method will never be passed duplicates and the remove method will never have to deal with the heap having duplicates. To be clear, your implementation would most likely work even if we were to test for duplicates; it’s just to help remove ambiguity surrounding grading and testing your implementation.

You may use both recursion and iteration for this assignment unlike your BST homework; use whichever you find more intuitive.