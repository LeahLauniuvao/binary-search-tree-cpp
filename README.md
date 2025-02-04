# Binary Search Tree in C++ 🌳  

## Overview  
This project implements a **Binary Search Tree (BST)** in C++ for efficient **searching, inserting, and removing** bid data from a CSV file. The tree structure allows for **fast lookups** and structured organization of data.

## Features  
- **Binary Search Tree Operations** (Insert, Search, Delete, In-Order Traversal).  
- **CSV File Parsing** to read bid data dynamically.  
- **Efficient Searching** with O(log n) complexity.  
- **Performance Timing** to measure execution speed.  

## 🛠 Installation & Compilation  

### **1️⃣ Clone the Repository**
```bash
git clone https://github.com/LeahLauniuvao/binary-search-tree-cpp.git
cd binary-search-tree-cpp
```

### **2️⃣ Compile the Code**
```bash
g++ -std=c++11 BinarySearchTree.cpp -o bst
```

### **3️⃣ Run the Program**
```bash
./bst
```

## 📂 File Structure  
```
binary-search-tree-cpp/
│── BinarySearchTree.cpp   # Main program
│── CSVparser.hpp          # CSV parsing header file
│── bids.csv               # Sample CSV file (optional)
│── README.md              # Project documentation
```

## 🖥 Example Usage  
```cpp
BinarySearchTree bst;
bst.Insert(Bid("1001", "Office Supplies", "General Fund", 300.50));
bst.Insert(Bid("1002", "Laptop", "Tech Fund", 1200.75));

Bid found = bst.Search("1001");
cout << found.title << " - " << found.amount << endl;
```

## 🚀 Future Enhancements  
- Implement **AVL Tree balancing** for optimized performance.  
- Expand CSV support with **stream-based reading**.  
- Improve **memory management** with smart pointers.  

## 📄 License  
This project is open-source under the **MIT License**.
