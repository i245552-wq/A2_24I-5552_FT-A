# 📚 Library Management System (Doubly Linked List)

## 📖 Overview
This project is a **Library Management System** implemented in **C++** using a **doubly linked list** data structure.  
It allows users to manage a list of books, supporting operations such as:
- Adding books at the beginning, end, or a specific position.
- Deleting books by ID.
- Displaying the list of books both forward and backward.

This project demonstrates understanding of **linked list implementation, pointer manipulation, and dynamic memory management** in C++.

---

## ⚙️ Features
- ➕ Add book at the beginning, end, or any given position.
- ❌ Delete a book using its unique Book ID.
- 🔁 Traverse and display all books in **forward** and **reverse** order.
- 🧠 Demonstrates practical use of **doubly linked list** structure.

---

## 🧩 Data Structure Used
Each book is represented as a node in a **doubly linked list**, with the following structure:

```cpp
struct Node {
    int BookID;
    string Title;
    string Author;
    Node* next;
    Node* prev;
};
