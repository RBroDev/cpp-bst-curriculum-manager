# C++ BST Curriculum Manager

An advising assistance tool built for the ABCU Computer Science department. This application parses course data and leverages a custom Binary Search Tree (BST) to manage complex prerequisite relationships, providing fast, alphanumeric retrieval of the full course catalog.

### 🛠️ Core Technologies
* **Language:** C++
* **Data Structure:** Binary Search Tree (BST)
* **Concepts:** CSV Parsing, Object-Oriented Design, Algorithmic Analysis (Big O)

### 🚀 Key Features
* **Efficient Retrieval:** Utilizes a BST to achieve $O(\log n)$ average search time for course details.
* **Alphanumeric Sorting:** Leverages in-order traversal for automatic, efficient catalog printing, eliminating the need for separate sorting algorithms.
* **Modular Architecture:** Clean separation of concerns with encapsulated `BinarySearchTree` and `Node` structures.
* **Robust Input Validation:** Custom string-splitting and two-pass verification ensure data integrity when parsing CSV course files.

### 📈 Algorithmic Analysis
To optimize performance, this project includes a comparative evaluation of data structures:
* **Vectors:** Efficient $O(1)$ loading, but inefficient $O(n \log n)$ sorting requirements.
* **Hash Tables:** Exceptional $O(1)$ average search, but unsuitable for generating ordered output.
* **Binary Search Tree (Selected):** Provides the optimal balance, keeping data naturally sorted for ordered output while maintaining efficient search capabilities.
