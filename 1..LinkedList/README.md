
<img src="../src/list.gif" />

# ``` Linked List ...  ```
### " Why did the linked list break up with the array? Because it wanted more space to grow and didn't want to be indexed! " 😜

## Overview
A linked list is a linear data structure where elements are stored in a non-contiguous manner. Each element, called a node, contains a data field and a reference to the next node in the sequence.

## Implementation
This repository contains Java implementations of a singly linked list and a doubly linked list.

### SinglyLinkedList.java
- Implements a singly linked list.
- Supports operations like insertion, deletion, traversal, and searching.

### DoublyLinkedList.java
- Implements a doubly linked list.
- Supports operations like insertion, deletion, traversal (forward and backward), and searching.

## ⏳ Time Complexity
- ### Singly Linked List: ➡️
    - Insertion at the beginning: ``` O(1) ``` ⚡
    - Insertion at the end: ``` O(n) ``` 🔄
    - Deletion: ``` O(n) ``` 🔄
    - Searching: ``` O(n) ``` 🔄
  
- ### Doubly Linked List: ↔️
    - Insertion at the beginning: ``` O(1) ``` ⚡
    - Insertion at the end: ``` O(n) ``` 🔄
    - Deletion: ``` O(n) ```🔄
    - Searching: ``` O(n) ``` 🔄 

## 📦 Space Complexity
- ➡️ Singly Linked List: ``` O(n) ``` 🔄
- ↔️ Doubly Linked List: ``` O(n) ``` 🔄

## Usage
### SinglyLinkedList.java
```java
public class Main {
    public static void main(String[] args) {
        SinglyLinkedList<Integer> list = new SinglyLinkedList<>();
        list.insertAtBeginning(5);
        list.insertAtEnd(10);
        list.insertAtEnd(15);
        list.delete(10);
        list.printList();
    }
}
```

### DoublyLinkedList.java
```java
public class Main {
    public static void main(String[] args) {
        DoublyLinkedList<Integer> list = new DoublyLinkedList<>();
        list.insertAtBeginning(5);
        list.insertAtEnd(10);
        list.insertAtEnd(15);
        list.delete(10);
        list.printListForward();
        list.printListBackward();
    }
}
```

## 🚀 Happy Coding! 🌟