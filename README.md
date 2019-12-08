# What-I-Learned-In-Week-13
### Array Methods
* Map, Filter, and Sort - are methods that loop through arrays and returns a new array based on certain conditions.

---
### Sort
* Stable Sort
* Bubble Sort

---
### Assignments
* Todo App - continued building off of arrow functions and mapping/filtering/sorting into new arrays and showing that data on the DOM.
* Linked List - has a head and tail of a node, which act like pointers.
  *  Node(a thing) - has a value and a next. The next is a pointer to the next one.

---
### Notes
* Spread Operator `[...array1, ...array2]` will join all the items in an array.
* Deconstruct ({target}) as a parameter is the same as: `const {target} = event;` or `const {querySelector, createElement} = document`.

* Scaling an app.
  * `O(n)` indexOf will go through the entire array.
  * `O(1)` push will take 1 operation. 
  * `O(n²)` is the handshake problem and exponentially bigger.
  * `O(log n)` you don't have to hit everything to complete by sorting the data.
