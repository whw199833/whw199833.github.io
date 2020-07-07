---
published: true
---
## First Post

How to correctly remove an element from a list during traversal?(In python)

One thing to notice is that if you directly remove and the pointer has already moved to the next position, while the next element. 

So you will miss one, right ?

There are two solutions.

1.Copy the list, operating on the list and traverse on the copy. Remember in Python 

"=" is like a pointer and you shoule use [:] to indicate a copy.

2.Starting from the end.


