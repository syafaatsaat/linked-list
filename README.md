# Linked List

Revision on Data Structures and this project is focused on Linked Lists, built 
with JavaScript for The Odin Project.

## Features

- append(value) - insert value at end of linked list
- prepend(value) - insert value in front of linked list
- size() - find number of nodes in linked list
- head() - returns the first value of linked list
- tail() - returns the last value of linked list
- at(index) - returns the value at the given index in the linked list
- pop() - removes the first/head node of the linked list
- contains(value) - returns true if value is inside the linked list, otherwise 
false
- findIndex(value) - returns index of value if it is inside the linked list, 
otherwise return -1
- toString() - prints linked list as a string in the format: ( value ) -> ( 
  value ) -> ( value ) -> null
- insertAt(index, ...values) - insert new nodes with the values given at the 
index given. if index given is out of bounds (< 0 or > size of linked list), 
throw RangeError
- removeAt(index) - remove node at the index given. similarly, if index given is 
out of bounds (< 0 or > size of linked list), throw RangeError