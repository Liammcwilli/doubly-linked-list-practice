# Doubly Linked List in JavaScript

This project contains an implementation of a doubly linked list in JavaScript. The code includes two main classes: `Node` and `DoublyLinkedList`.

## Node Class

The `Node` class represents individual nodes in the doubly linked list. Each node contains:

- `data`: Holds the value of the node.
- `next`: Points to the next node in the list.
- `previous`: Points to the previous node in the list.

### Methods

- `setNextNode(node)`: Sets the reference to the next node.
- `setPreviousNode(node)`: Sets the reference to the previous node.
- `getNextNode()`: Retrieves the reference to the next node.
- `getPreviousNode()`: Retrieves the reference to the previous node.

## DoublyLinkedList Class

The `DoublyLinkedList` class manages the doubly linked list, maintaining references to both the head and tail nodes.

### Methods

- `addToHead(data)`: Adds a new node containing the given data to the beginning of the list.
- `addToTail(data)`: Adds a new node containing the given data to the end of the list.
- `removeHead()`: Removes the head node from the list.
- `removeTail()`: Removes the tail node from the list.
- `removeByData(data)`: Removes a node with the specified data from the list.
- `printList()`: Prints the entire list, from head to tail, for visualization.

## Usage

To use this implementation:

1. Import the `DoublyLinkedList` class from `./DoublyLinkedList`.
2. Create a new doubly linked list instance.
3. Perform operations like adding nodes to the head or tail, removing nodes by data, and printing the list.