# cpp-single-linked-list
## Additional languages: [Русский](Russian/README.md)

## Single linked list realisation.

#### Features:

  * Realisation of iterators.
  * Realisation of comparison operators ==, !=, <, >, <=, >=.
  * Realisation of swapping the contents of two lists using swap method and swap template function.
  * Construction of single linked list based on initializer_list.
  * Realisation of copy constructor and assignment operator.

#### Main methods:
  * **GetSize.** Returns the number of items in the list.
  *	**IsEmpty.** Returns true if the list is empty, or false otherwise.
  *	**PushFront.** Inserts an element at the beginning of a single-linked list.
  *	**Clear.** Clears the list.
  *	**PopFront.** Removes the first item of a non-empty list in O(1) time. Does not throw exceptions.
  *	**InsertAfter.** Inserts a new value into the list after the position passed to InsertAfter method in O(1) time.
  *	**EraseAfter.** Removes an element from the list after the position passed to EraseAfter method in O(1) time.
  *	**before_begin** и **cbefore_begin.** Returns iterator that refer to the mock position before the first item in the list.