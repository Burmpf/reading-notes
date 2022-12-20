# Data Structures and Algos

## Sources
### Videos
[Basic Recursion](https://www.youtube.com/watch?v=vPEJSJMg4jY)

[Data Structures in 15 Minutes](https://www.youtube.com/watch?v=sVxBVvlnJsM)

[BigO explained](https://www.youtube.com/watch?v=sVxBVvlnJsM)

### Articles
[Basic Data Structures](https://towardsdatascience.com/8-common-data-structures-every-programmer-must-know-171acf6a1a42)

[Why BigO](https://triplebyte.com/blog/why-you-should-learn-big-o-and-stop-hacking-your-way-through-algorithms)


## Notes

#### Recursive Functions
- recursion is broken down into a base case and recursive case (else)
  - recursive case is when the function calls itself
  - base case is when it does not call itself again to avoid a loop (if)
- recursion is a way to more simply write code
- you have to tell it when to stop "recursing"

#### Data Structures in 15 mins
- all data structures are good and bad at some things. None are perfect
- 5 most data structures you should know
  1.  Linked Lists- has 2 parts and made up of nodes. It has a pointer and a value. The value can be anything and the pointer points you to the next node. good for adding and removing nodes. Not good for moving them
  2.  Array- Super common in all languages. Tracks item location. good for retrieving items. bad for adding items. 
  3.  Hash Table- OBJ in JS and a Dictionary in PY. key gets sent through a hashing function and will give a memory location. a collision is when 2 keys hash to the same location. good for adding and retreiving but bad because of potential collisions
  4.  Stack+Queue- stack is last in/first out. Queue is first in/first out. good for efficiency but bad are limited in use case.
  5.  Graphs+Trees- graphs are nodes pointing to other nodes. Social media store data in graphs. tree is a graph where data branches out in 1 direction. graphs can only have 2 childen. 1 is more than node, the other more. good for efficency but bad because they can become unbalanced. 

### BigO explained
(this did not help my understanding of BigO)
- things to remember:
   1. Different steps get added
   2. drop constants
   3. different inputs=> different variables
   4. drop non-dominate terms
- BigO is how time scales with respect to some input variables
- O(1)- constant time no matter the size
- O(N)- scales linearly/proportionally based on size of data
- O(N^2)-  ???