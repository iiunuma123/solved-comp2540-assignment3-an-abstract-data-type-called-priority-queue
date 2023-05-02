Download Link: https://assignmentchef.com/product/solved-comp2540-assignment3-an-abstract-data-type-called-priority-queue
<br>
For this assignment, you will write a computer program to implement an Abstract Data Type called Priority Queue. A priority queue is like a regular queue, but each element has a “priority” associated with it. In a priority queue, an element with high priority is served before an element with low priority. If two elements have the same priority, they are​ ​served​ ​according​ ​to​ ​their​ ​enqueue​ ​order​ ​in​ ​the​ ​queue.




Implement​ ​the ​​Priority​ ​Queue​ ​as​ ​an​ ​ADT​  ​using​ ​two​ ​different ​ underlying​ ​ representations:​

<ol>

 <li>Static ​ array​​ ​that​ ​stores​ ​the​ ​elements​ ​in​ ​priority​ ​order</li>

 <li>Linked​ ​list​ ​that​ ​stores​ ​the ​elements​​ ​in​ ​priority​ ​order</li>

</ol>




Regardless the underlying representations (array, a linked list) your Priority Queue Class should allow any programmer to store any element (data) without understand or knowing the​ ​details​ ​of​ ​the​ ​underlying​ ​representation.




Your​ ​Priority​ ​Queue​ ​ADT​ ​should​ ​provide​ ​the​ ​following​ ​interfaces​  ​(functions)

<ol>

 <li><strong><em>enqueue(element, priority, queue):</em></strong> add an element into the queue at the appropriate position in the queue based on the associated priority. If the priority parameter is missing, assign to the element 5 as default priority, which is the lowest​ ​</li>

 <li><strong><em>deque(queue):</em></strong> remove the element with the highest priority from the queue. If two elements have the same priority, they are served according to their order in the​ ​</li>

 <li><strong><em>peek(queue):</em></strong>​​ ​return​ ​the​ ​element​ ​to​ ​be​ served​ ​ ​from ​ the​ ​ queue​ ​ without​ ​ removing​ ​ it​</li>

 <li><strong><em>IsRegular(queue):</em></strong> return true if all the current elements in the queue have the same ​ ​</li>

 <li><strong><em>size(queue):</em></strong>​​ ​returns ​ the​ ​ total​ ​ number​ ​ of​​ elements​ ​ in​ ​ the​ ​ ​ 6. <strong><em>isEmpty(queue):</em></strong>​​ ​returns​ ​true​ ​if​ ​the​ ​queue​ ​is​ empty.​</li>

 <li><strong><em>isFull(queue):</em></strong>​​ ​returns​ ​true​ ​if​ ​the​ ​queue​ ​is​ ​</li>

 <li><strong><em>display(queue):</em></strong>​​ ​prints​ ​all​ ​the​ ​elements​ ​in ​the​​ ​queue​ ​with ​​their​ ​</li>

</ol>

<strong>Grading: </strong>

<ul>

 <li>Correctness​ ​60%</li>

 <li>Algorithms​ ​Design​ ​(30%)</li>

 <li>Pair ​ work​ ​ (10%)​</li>

</ul>