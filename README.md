 Java Quiz System Project

 Project Overview
 Console-based Quiz Management System
 Supports Java, DSA, and Database quizzes
 Loads questions from text files
 Handles short-answer and multiple-choice quizzes
 Calculates and displays final score

 Files Used
 QuestionLoader.java → Loads quiz questions
 QuizManager.java → Manages quiz execution
QuizSystem.java → Main class and program entry point
External text files for storing questions

---

 Core Classes
 `Question` class
 `QuestionLoader` interface
 `ShortAnswerLoader` class
 `ChoiceLoader` class
 `QuizManager` class
 `QuizSystem` class (main class)

 OOP Concepts Used
Encapsulation → `Question` class
Abstraction → `QuestionLoader` interface
Polymorphism → `load()` method overriding
Inheritance/Implementation→ Loader classes implement interface

---

 Java Concepts Used
 ArrayList
 Scanner
 BufferedReader
 FileReader
 Exception Handling (try-catch)
 Loops (for, do-while)
 Switch-case

Program Flow
1. Load files
2. Create loaders
3. Read quiz questions
4. Display menu
5. User selects subject
6. Quiz starts
7. Evaluate answers
8. Show final score

 File Breakdown

 QuestionLoader.java
 Defines `Question` model
 Interface for loading questions
 `ShortAnswerLoader` handles 2-part format
 `ChoiceLoader` handles 6-part MCQ format
 QuizManager.java
 Controls quiz execution
 Displays questions
 Collects user answers
 Checks correctness
 Tracks score

QuizSystem.java (Main Class)
 Defines file paths
 Initializes loaders
 Loads all subjects
 Displays subject menu
 Calls `QuizManager.startQuiz()`

 Advantages
 Simple modular design
 Easy to extend
 Supports multiple subjects
  Reusable code
 Uses all pillars of OOP concepts

 Conclusion
 Demonstrates practical Java programming
 Uses file handling and OOP effectively
 Good example of a modular console application



THANK YOU
