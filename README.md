# Linked-Lists
This repository describes the theory behind linked list data structures, as well as the different methods applied to them.

## What is a *linked list*?

A linked list is a linear data structure consisting of a collection of elements called nodes, where each node contains data and a pointer to the next node.<br>
Linked lists store elements in sequential order, but not necessarily in contiguous memory locations, because each node is stored in different memory locations.

## Types of linked lists

1. [Singly linked lists](https://github.com/SamiIonesi/Singly_Linked_Lists/tree/main)
    - each node contains data and a pointer to the next node
    - traversal is unidirectional, only forward
2. Doubly linked lists
    - each node contains data an two pointers: one to the next node and one to the previous node
    - traversal is bidirectional, forward and backward
3. Circular linked lists
    - the last node is pointed to the head, forming a circle
    - can be singly or doubly linked

## Advantages

- the best advantage of a linked list is that it can grow and shrink in size as needed
- the memory is allocated dynamicaly, which means the size is variable
- adding or deleting an element is more efficient because is does not require shifting element like in arrays, especialy at the begining or at the end of a linked list

## Disavantages

- require extra memory for saving each node pointer
- accsessing an element by index (O(n))is slower compare to arrays (O(1))

## Methods
### For a *Singly Linked List*

#### 1. Insertion methods
   - append(value)
   - prepand(value)
   - insert(value)
#### 2. Deletion methods
   - delete
#### 3. Search methods
   - search(value)
#### 4. Utility methods
   - [getLength()](https://github.com/SamiIonesi/Singly_Linked_Lists/blob/main/README.md#getlength)
   - [display()](https://github.com/SamiIonesi/Singly_Linked_Lists/blob/main/README.md#--display)
   - [recursiveDisplay(Node)](https://github.com/SamiIonesi/Singly_Linked_Lists/blob/main/README.md#--recursivedisplaynode)
   - [create(array, sizeOfArray)](https://github.com/SamiIonesi/Singly_Linked_Lists/blob/main/README.md#--createarray-sizeofarray)
   - reverse()
   - isEmpty()
   - [countNodes()](https://github.com/SamiIonesi/Singly_Linked_Lists/blob/main/README.md#--sumofnodesvalue)
   - [sumOfNodesValue()](https://github.com/SamiIonesi/Singly_Linked_Lists/blob/main/README.md#--sumofnodesvalue)
   - [maxElement()](https://github.com/SamiIonesi/Singly_Linked_Lists/blob/main/README.md#--maxelement)
