# 📚 DSA Tutorial Application

> An interactive **C++ Data Structures & Algorithms learning application** designed to help students understand, practice, and test their knowledge of fundamental data structures through algorithms, hands-on exercises, and quizzes.

---

## 🎯 About the Project

This project was developed as part of my **Data Structures & Algorithms (DSA)** coursework during my **3rd semester of Software Engineering**.

Instead of creating a program that only performs data structure operations, I designed it as a **tutorial-based learning application**.

The application combines:

**📖 Learn → 💻 Practice → 🧠 Test → 🏆 Track Your Score**

The main goal is to make fundamental DSA concepts more interactive and easier to understand by allowing the user to:

- View how an algorithm works
- Experiment with the algorithm themselves
- Work with their own input
- Observe sorting processes step-by-step
- Answer topic-based MCQs
- Receive a score at the end of each module

---

# 🌟 Key Features

### 📊 1. Arrays

The Array module provides several fundamental operations:

- 🔎 Search
- 🔄 Sort
- ✏️ Update
- ➕ Insert
- 🗑️ Delete

Each operation provides three learning modes:

```text
📖 View Algorithm
       ↓
💻 Try It Yourself
       ↓
🧠 Take Quiz
       ↓
🏆 View Score
```

The practice mode allows the user to decide the length of the array and work with their own input rather than relying on a fixed example.

### 🔗 2. Linked Lists

The Linked List module introduces linked-list concepts through interactive operations.

It covers operations such as:

➕ Insertion
🗑️ Deletion
🔎 Searching
✏️ Updating
📋 Displaying elements

The module is designed to help the user understand how elements are connected and manipulated rather than simply showing the final result.

### 📥 3. Queue

The Queue module demonstrates the fundamental FIFO (First In, First Out) principle.

Users can interact with queue operations and learn how elements are added, removed, and managed.

The module includes:

➕ Enqueue
🗑️ Dequeue
👁️ Display
📖 Algorithm explanation
💻 Practice mode
🧠 Quiz

### 📚 4. Stack

The Stack module demonstrates the LIFO (Last In, First Out) principle.

Users can practice common stack operations and understand how elements are added and removed.

The module includes:

➕ Push
🗑️ Pop
👁️ Display
📖 Algorithm explanation
💻 Practice mode
🧠 Quiz
🔄 Interactive Learning Structure

One of the main ideas behind this project is that the user should not simply read an algorithm or see its final output.

---

Each major topic follows a learning cycle:

📖 View Algorithm

The application explains the algorithm and its logic.

💻 Try It Yourself

The user can interact with the operation and make their own decisions.

For example, in the Array module, the user can determine the array length and then perform the selected operation on their own input.

🧠 Take the Quiz

After learning and practicing the topic, the user can test their understanding through MCQ-based questions.

🏆 View Your Score

The application calculates the user's score and displays the result for that module.

This creates a simple learning progression:

```text
       📖 LEARN
          ↓
      💻 PRACTICE
          ↓
       🧠 TEST
          ↓
      🏆 SCORE
```

🔥 Highlight Feature — Step-by-Step Sorting Visualization

One of the most important features of this application is the way sorting algorithms are demonstrated.

Instead of displaying only the final sorted array, the application shows the array after each important step or swap.

For example:

```text
Initial Array

[ 5  2  8  1 ]

        ↓

First comparison / swap

[ 2  5  8  1 ]

        ↓

Next comparison / swap

[ 2  5  1  8 ]

        ↓

Next step

[ 2  1  5  8 ]

        ↓

Final Result

[ 1  2  5  8 ]
```

This makes algorithms such as Bubble Sort and Selection Sort easier to visualize because the user can follow the transformation of the array instead of seeing only the final answer.

This feature was particularly important to me because it turns the application from a simple DSA implementation into a more educational and visual learning tool.

🔎 Searching

The application demonstrates searching techniques through the Array module.

Users can:

Learn the searching algorithm
Practice searching with their own data
Observe the result
Test their knowledge through the quiz

The application also handles the required preparation for algorithms where ordering is important.

For example, if the data is not suitable for Binary Search, the program can prepare the data before performing the search.

🔄 Sorting Algorithms

The application demonstrates sorting algorithms and focuses on explaining the process rather than only producing the final result.

Sorting operations can show intermediate states of the array, allowing the user to understand:

Comparisons
Swaps
Passes
Intermediate arrays
Final sorted output

This makes the application useful as a learning aid for students who are beginning to study sorting algorithms.

🧠 Quiz & Scoring System

Each major learning module contains an MCQ-based quiz.

The quiz system allows users to:

Select a topic
Answer questions
Receive feedback/results
Calculate their score
View their total performance for the module

The score provides immediate feedback after completing the learning activity.

```text
📖 Learn the Topic
       ↓
💻 Practice
       ↓
🧠 Answer MCQs
       ↓
📊 Calculate Score
       ↓
🏆 View Result
```
---

## 🧩 Main Modules
Module	Main Focus
📊 Arrays	Search, Sort, Insert, Update, Delete
🔗 Linked Lists	Linked-list operations and manipulation
📥 Queue	FIFO operations
📚 Stack	LIFO operations

Each module is designed around the same educational approach:

```text
Algorithm → Practice → Quiz → Score
```

---

## 🛠️ Technologies Used
Technology	Purpose
💻 C++	Application development
🧠 Data Structures & Algorithms	Core concepts and implementation
🖥️ Console Interface	User interaction and output
🌱 Git	Version control
🐙 GitHub	Source code management and project documentation

---

## 📁 Project Structure

```text
semester-3-dsa-tutorial-application/
│
├── 📄 prototype.cpp
│
├── 📂 Demo/
│   └── .gitkeep
│
├── 📂 Screenshots/
│   └── .gitkeep
│
└── 📄 README.md
```

The application is currently contained in a single C++ source file, while the repository is organized into dedicated folders for the demonstration video and screenshots.

---

## ⚙️ How to Run
Requirements

You need:

C++ compiler
C++ development environment such as Dev-C++, Code::Blocks, Visual Studio, or VS Code with a C++ compiler
Run the Application
1. Clone the repository
```text
git clone https://github.com/Amina-SE/semester-3-dsa-tutorial-application.git
```

2. Open the project

Open:

```text
prototype.cpp
```

in your preferred C++ development environment.

3. Compile

Compile the source file using a C++ compiler.

4. Run

Run the generated executable and follow the menu displayed in the console.

---

## 🧠 DSA Concepts Practiced

This project provided practical experience with:

Arrays
Linked Lists
Stacks
Queues
Searching
Sorting
Insertion
Deletion
Updating
Traversal
Algorithm implementation
Algorithm analysis
User input handling
Menu-driven programming
Quiz and scoring logic

---


🚀 Future Improvements

Possible future improvements include:

🎨 Graphical User Interface
📊 Visual graphs for algorithm complexity
⏱️ Algorithm execution-time comparison
🧩 More data structures
🌳 Trees
🕸️ Graphs
🔥 Heaps
#️⃣ Hash Tables
📈 More advanced sorting algorithms
🧠 Larger quiz question banks
🏆 Overall progress tracking
💾 Saving user scores
📊 Performance analytics
🌐 Conversion into a desktop GUI or web-based learning platform

---

## 👩‍💻 Author
Amina Batool

Software Engineering Student
Riphah International University

🔗 GitHub:
https://github.com/Amina-SE

📜 License

This project is available under the license included in this repository.

<div align="center">
⭐ DSA Tutorial Application

Learn • Practice • Understand • Test

Built with C++ and a passion for understanding Data Structures & Algorithms.

</div>