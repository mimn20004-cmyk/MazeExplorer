# Maze Exploration Console
### Data Structures & Algorithms Project – C++

---

## 1. Project Overview

Maze Exploration Console is a C++ console-based application developed as part of the Data Structures course at Misr University for Science and Technology (MUST).

The project focuses on exploring maze environments using different data structures and searching algorithms. It demonstrates how fundamental computer science concepts can be combined to solve a practical problem through an organized software application.

يهدف المشروع إلى تطبيق مفاهيم Data Structures وAlgorithms عمليًا من خلال بناء برنامج لاستكشاف المتاهات والتعامل مع مساراتها.

## 2. Project Aim

The main aim of this project is to develop a maze exploration system that demonstrates the practical use of different data structures and algorithms.

The project also aims to:

- Apply theoretical concepts through practical implementation.
- Understand how data structures support different algorithms.
- Improve problem-solving and algorithmic thinking.
- Practice modular programming using C++.
- Develop teamwork and collaborative programming skills.
- Gain experience with Git and GitHub.

## 3. Project Concept

A maze consists of a grid of cells containing different types of locations, including accessible paths, walls, a starting point, and a destination.

The application is designed to process this environment and explore possible paths between the starting point and the destination using different search techniques.

The project focuses on demonstrating how different data structures can support the exploration process and organize the information generated during execution.

ببساطة، البرنامج بيتعامل مع متاهة مكونة من خلايا، وبيستخدم طرق بحث مختلفة لاستكشافها والوصول إلى نقطة النهاية.

## 4. Data Structures Used

The project is planned to implement the following data structures manually using C++.

### 4.1 Stack

**Purpose:** Used to support Depth-First Search (DFS).

Stack follows the LIFO (Last In, First Out) principle.

يُستخدم لتنظيم الخلايا أثناء استكشاف المتاهة باستخدام DFS.

### 4.2 Queue

**Purpose:** Used to support Breadth-First Search (BFS).

Queue follows the FIFO (First In, First Out) principle.

يُستخدم لتنظيم الخلايا المنتظرة للاستكشاف أثناء تنفيذ BFS.

### 4.3 Linked List

**Purpose:** Used to organize and maintain records of visited maze cells.

تُستخدم لتخزين وتنظيم سجلات الخلايا التي تمت زيارتها أثناء عملية الاستكشاف.

### 4.4 Binary Search Tree (BST)

**Purpose:** Used to organize cell-related information and support efficient searching operations.

تُستخدم لتنظيم بيانات الخلايا وإجراء عمليات البحث اعتمادًا على ترتيب المفاتيح.

## 5. Algorithms Used

The project includes the following algorithms:

### 5.1 Depth-First Search (DFS)

An exploration algorithm that follows a path as deeply as possible before returning to explore alternative paths.

تُستخدم لاستكشاف أحد المسارات بعمق، ثم الرجوع عند الوصول إلى طريق مسدود.

### 5.2 Breadth-First Search (BFS)

An exploration algorithm that visits neighboring cells level by level.

تُستخدم لاستكشاف الخلايا الأقرب أولًا، ويمكنها إيجاد أقصر مسار عندما تكون جميع الانتقالات متساوية التكلفة.

### 5.3 Linear Search

A searching algorithm that checks elements sequentially until the required element is found or the search reaches the end of the data.

تُستخدم للبحث داخل السجلات المخزنة عن طريق فحص العناصر بالتتابع.

## 6. Project Architecture

The project follows a modular structure. Each directory is responsible for a specific part of the application.

This organization helps team members work independently and makes future integration, testing, and maintenance easier.

### Directory Structure

```text
MazeExplorer/
│
├── Algorithms/
│   ├── BFS.h
│   └── DFS.h
│
├── BST/
│   └── BST.h
│
├── LinkedList/
│   └── LinkedList.h
│
├── Maze/
│   └── Maze.h
│
├── Queue/
│   └── Queue.h
│
├── Report/
│
├── Stack/
│   └── Stack.h
│
├── Tests/
│
├── main.cpp
│
└── README.md
```

## 7. Files and Directories Description

This section explains the responsibility of each file and directory to help contributors understand where to work.

### 7.1 Algorithms/

Contains the searching and maze exploration algorithms.

- **BFS.h:** Contains the Breadth-First Search algorithm.
- **DFS.h:** Contains the Depth-First Search algorithm.

### 7.2 BST/

- **BST.h:** Contains the Binary Search Tree class and its related operations.

### 7.3 LinkedList/

- **LinkedList.h:** Contains the Linked List implementation, its node structure, and related operations.

### 7.4 Maze/

- **Maze.h:** Contains the Maze class and the basic operations responsible for representing and managing the maze environment.

### 7.5 Queue/

- **Queue.h:** Contains the Queue class and its related operations.

### 7.6 Stack/

- **Stack.h:** Contains the Stack class and its related operations.

### 7.7 Tests/

Reserved for testing individual components and verifying that the application works correctly.

سيتم استخدام هذا المجلد لتنظيم الاختبارات الخاصة بأجزاء المشروع المختلفة واختبارات تكامل النظام.

### 7.8 Report/

Reserved for project documentation, explanations, test results, and final submission materials.

### 7.9 main.cpp

The main entry point of the application.

It is responsible for starting the program, coordinating the main application flow, and connecting the different components.

### 7.10 README.md

Provides general information about the project, its structure, technologies, and development status.

## 8. Technologies and Tools

| Technology / Tool | Purpose |
|---|---|
| C++ | Main programming language |
| Visual Studio Code | Development environment |
| Git | Version control |
| GitHub | Source code hosting and team collaboration |

## 9. Development Approach

The project is developed through separate components to make collaboration and integration easier.

Each team member is responsible for a specific component, including its implementation, understanding, and testing.

After individual development, the components will be integrated into the main application.

All team members are expected to understand the overall project, not only their assigned components.

## 10. Team Structure

The project is developed by a team of five members.

The work is divided into five main responsibilities:

1. Stack and DFS.
2. Queue and BFS.
3. Linked List and Linear Search.
4. Binary Search Tree (BST).
5. Maze Management and System Integration.

All members share responsibility for understanding, testing, and explaining the complete application.

## 11. Academic Information

**University:** Misr University for Science and Technology (MUST)  
**Course:** Data Structures  
**Project:** Maze Exploration Console  
**Programming Language:** C++  
**Team Size:** 5 Members

---