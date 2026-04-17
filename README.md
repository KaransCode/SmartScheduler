# 📅 Smart Scheduler System (Pro Edition)

![C++](https://img.shields.io/badge/C++-17-blue.svg)
![Qt](https://img.shields.io/badge/Qt-6.x-green.svg)
![Build](https://img.shields.io/badge/build-passing-brightgreen)

The **SmartScheduler System** is a native C++ desktop application with a modern Qt Graphical User Interface (GUI). It acts as an academic timetable manager and an OS-level process simulator, specifically designed to demonstrate the practical application of advanced Data Structures, Algorithms, and Object-Oriented Programming (OOP) concepts.

This project was developed for the **Technical Training (25CAP-652)** course (MCA - Data Science) at Chandigarh University.

---

## ✨ Features & Course Outcomes (CO)

### 1. Matrix Timetable Module
A visual, weekly horizontal calendar for managing lectures, labs, and breaks.
* **Graph Conflict Detection (CO5):** Models the timetable as an Adjacency Matrix. Uses Breadth-First Search (BFS) graph traversal to detect and prevent room/time scheduling clashes.
* **LRU Cache Optimization (CO4):** Employs a Least Recently Used (LRU) mechanism (Doubly-Linked List + Hash Map) for O(1) retrieval of recently accessed slots.

### 2. Job Scheduler Module
Simulates operating system CPU scheduling, managing queues of High-Priority, Low-Priority, and I/O-bound jobs.
* **OOP & Runtime Polymorphism (CO3):** Utilizes an abstract base class (`ScheduleItem`) and virtual functions (`execute()`) to dynamically handle different job types at runtime.
* **Scheduling Algorithms:** Implements **First Come First Serve (FCFS)** and **Priority Scheduling** to calculate waiting and turnaround times.

### 3. Logic Utilities
A built-in mathematical toolkit and array checker.
* **Infix to Postfix/Prefix Machine (CO1):** Uses a Stack-based modified Shunting Yard algorithm to parse human-readable formulas into machine-readable notations, respecting operator precedence.
* **Data Integrity Checks (CO2):** Uses nested iterations over C++ vectors/arrays to scan for and detect duplicate IDs.

---

## 🛠️ Tech Stack & Architecture
* **Core Logic:** Pure C++ (Standard Template Library: `std::vector`, `std::stack`, `std::queue`).
* **Frontend/GUI:** Qt Framework (C++) using `QMainWindow`, `QTableWidget`, `QMessageBox`, and modern Qt Style Sheets (QSS) for a vibrant dark mode theme.
* **Architecture:** Model-View-Controller (MVC) pattern, cleanly separating the backend data structures from the UI presentation logic.
* **Build System:** CMake.

---

## 🚀 Installation & Setup

### Prerequisites
* [Qt Creator](https://www.qt.io/download-open-source) installed (with Qt 6.x and a compatible compiler like MinGW or MSVC).
* Git.

### Build Instructions
1. **Clone the repository:**
   ```bash
   git clone [https://github.com/YourUsername/SmartScheduler.git](https://github.com/YourUsername/SmartScheduler.git)
   cd SmartScheduler

Open in Qt Creator:

Open Qt Creator.

Go to File > Open File or Project...

Select the CMakeLists.txt (or .pro) file inside the cloned directory.

Configure the Kit:

Select your desktop kit (e.g., Desktop Qt 6.x.x MinGW 64-bit) and click Configure Project.

Build and Run:

Click the Hammer icon (Ctrl+B) to build the project.

Click the green Play button (Ctrl+R) to run the application.

📂 Project Structure
Plaintext
SmartScheduler/
├── Headers/
│   └── mainwindow.h         # Qt UI Definitions & Declarations
├── Sources/
│   ├── main.cpp             # Application Entry Point
│   └── mainwindow.cpp       # Core C++ Logic (CO1-CO5) & UI Implementation
├── CMakeLists.txt           # Build configuration
└── .gitignore               # Ignores Qt build artifacts


👥 Contributors
Karan Singh (UID: 25MCD10020) - MCA Data Science

📄 License
This project is licensed under the MIT License.


### How to use this:
1. Open your project repository on GitHub.
2. Click the **"Add a README"** button (or click the pencil icon to edit your existing `README.md`).
3. Copy the entire text inside the code block above.
4. Paste it into the GitHub editor.
5. Update your GitHub username in the **Clone the repository** section and add your second team member's name at the bottom.
6. Scroll down and click the green **"Commit changes"** button!
