# 🎓 University Code Portfolio

This repository serves as a comprehensive collection of assignments, lab exercises, and projects completed during my 3rd-semester university studies. The work spans across multiple paradigms and environments, demonstrating a progression from low-level memory management to functional programming and statistical data analysis.

Below is a detailed breakdown of the courses and the projects within them.

---

## 🛠️ Effective Programming Techniques (TEP) - Course Projects
**Technologies:** `C++` | **Folder:** `3 Semester/Effective Programing Technicues/`

This repository section contains a series of projects developed for the Effective Programming Techniques course at Wrocław University of Science and Technology. The projects progress from manual memory management in C++98 to advanced template programming and modern C++11 move semantics. All implementations strictly follow a policy of no unjustified exceptions and prioritize high-quality object-oriented design.

### List 1: Dynamic Allocation and Memory Management
This assignment focuses on the mechanics of dynamic memory allocation using the `new` and `delete` operators. It explores the differences between stack and heap allocation, as well as the implementation of multi-dimensional arrays using double pointers. The project includes the development of the first `Table` class, which manages an integer array and demonstrates the use of default, parameterized, and copy constructors to prevent memory leaks.

### List 2: Operator Overloading and Large Numbers
The second list introduces operator overloading as a tool to create more intuitive and readable code. The primary task is the creation of a `Number` class capable of storing and performing arithmetic on arbitrarily large integers stored in dynamic arrays. It requires manual implementation of the assignment operator and arithmetic symbols like `+`, `-`, `*`, and `/`, ensuring that operations do not rely on standard integer types which would limit the numerical range.

### List 3: Prefix Notation Expression Trees
This project involves building a system to parse and evaluate mathematical formulas provided in Polish (prefix) notation. Using `Tree` and `Node` classes, the program constructs a non-binary tree where operators serve as internal nodes and variables or constants serve as leaves. The implementation features an object-oriented parsing mechanism that automatically repairs incomplete expressions by adding default values or ignoring redundant arguments.

### List 4: Template Programming and Generic Results
The fourth assignment extends the previous work by utilizing C++ templates to allow for reusable, type-independent code. A key component is the `Result` template class, which encapsulates either a successful return value or a list of error objects. This list also explores template specialization, specifically for void types, to handle methods that do not return a value but may still encounter errors during execution.

### List 5: Smart Pointers and Move Semantics
This list introduces modern C++ features, specifically the automation of memory management through custom smart pointers and the optimization of resource transfers. By implementing a template-based smart pointer with reference counting, the project eliminates manual `delete` calls and prevents double-free errors. Additionally, it introduces move semantics through move constructors and move assignment operators, significantly reducing the overhead of copying large data structures like expression trees.

### Mini-Project: LcVRP Genetic Algorithm Optimizer
The final project is a comprehensive optimizer for the Limited Capacitated Vehicle Routing Problem (LcVRP) based on a Genetic Algorithm. It integrates the skills from all previous lists, including custom memory management and object-oriented design, to evolve a population of solutions through crossover and mutation. The system consists of a `GeneticAlgorithm` manager, an `Individual` class representing potential solutions, and an `Evaluator` to load and score problem instances.

---

## 🧠 Programming Paradigms - Course Projects
**Technologies:** `Scala`, `OCaml`, `Java` | **Folder:** `3 Semester/Programing Paradygmaths/`

This section explores diverse ways of structuring software. The coursework transitions from pure functional programming to advanced Object-Oriented design patterns, heavily contrasting the two methodologies.

### Lists 1-6: Functional Programming Foundations
These assignments focus on the core concepts of the functional paradigm using OCaml and Scala. They involve implementing recursive algorithms, utilizing complex pattern matching, and managing immutable data structures. The lists explore list processing, higher-order functions, and tail recursion without relying on standard imperative loops or mutable states.

### List 7: Object-Oriented Design and Visitor Pattern
This project completely shifts the paradigm to Object-Oriented Programming (OOP) using Java and Scala. The core task involves modeling a dynamic system—specifically a kitchen environment containing varied items like plates, cutlery, elves, and dishwashers. It heavily emphasizes the implementation of structural design patterns, utilizing the **Visitor Pattern** (`IVisitor`, `KitchenSorter`) to cleanly sort and process heterogeneous collections of kitchen items without polluting their base classes.

### List 8: Functional Expression Evaluator
The final functional project involves building a sophisticated mathematical expression evaluator in Scala. Using custom `Node` structures, the assignment demonstrates how to parse, represent, and evaluate abstract syntax trees strictly using functional paradigms, recursion, and immutable states.

---

## 📊 Probability and Statistics - Course Projects
**Technologies:** `R` | **Folder:** `3 Semester/Propability and Statistics/`

This section contains a series of analytical scripts and data projects developed for the Probability and Statistics course using R. The work spans from foundational probabilistic models to complex descriptive data analysis.

### Lists 1-5: Statistical Foundations and Probability
These assignments focus on understanding core probability distributions, random variables, and expected values. The R scripts simulate probabilistic models and perform foundational statistical computations, reinforcing theoretical mathematical concepts through computational exercises.

### Lists 6-7: Real-World Data Analysis
The final lists transition to practical data science, applying statistical tests, hypothesis testing, and descriptive analysis to real-world datasets. Utilizing provided data such as housing prices (`mieszkania.csv`), demographic weight statistics (`waga1.csv`), and bacterial growth tracking (`bakteria.csv`), these projects demonstrate data parsing, statistical inference, and the extraction of analytical insights using R markdown.

---
