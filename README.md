# OOP C++ Programming Activity

## Student Details
- **Student Name:** Vedant Sadanand Alurkar
- **PRN:** AD2652
- **Class/Division:** Sy-F
- **Course Name:** Object-Oriented Programming (OOP)
- **Course Code:** ADPC303

---

## Units Covered
1. **Unit I — C++ Basics & Core OOP** (`UNIT I/`)
2. **Unit II — Inheritance** (`UNIT 2/`)
3. **Unit III — Polymorphism** (`UNIT 3/`)

---

## Unit I: C++ Basics & Core OOP

### List of Programs

| # | Title | Folder | Main Concept | Description |
|---|-------|--------|--------------|-------------|
| 1 | Basic Data Types | `UNIT I/Program_01` | Fundamental Data Types | Demonstrates basic data types (`int`, `char`, `float`) and standard stream I/O. |
| 2 | Conditional Statements (if-else) | `UNIT I/Program_02` | Selection Control Structure | Checks pass/fail criteria using condition checking with `if-else`. |
| 3 | Loops and Arrays | `UNIT I/Program_03` | Arrays and Iteration | Demonstrates 1D array traversal using a standard `for` loop. |
| 4 | User-Defined Functions | `UNIT I/Program_04` | Modular Functions | Demonstrates function prototyping, parameter passing by value, and return values. |
| 5 | Classes and Objects | `UNIT I/Program_05` | Class & Object Basics | Encapsulates student data and behaviors into a class with object instances. |
| 6 | Constructor and Destructor | `UNIT I/Program_06` | Object Lifecycle | Demonstrates automatic initialization via constructor and cleanup via destructor. |
| 7 | Static Data Members | `UNIT I/Program_07` | Static Class Members | Tracks total object creations using a shared class-level static counter. |
| 8 | Inline and Friend Functions | `UNIT I/Program_08` | Inline & Friend Functions | Accesses private members via an inline getter and a non-member friend function. |


## Unit II: Inheritance

### List of Programs

| # | Title | Folder | Description |
|---|-------|--------|-------------|
| 1 | Basic Single Inheritance | `UNIT 2/Program_01` | A `Person` base class is extended by a `Student` derived class, which adds a roll number and displays both name and roll number. |
| 2 | Protected Member Access | `UNIT 2/Program_02` | An `Employee` base class exposes a protected `name` member which a `Developer` derived class accesses directly to display employee and language details. |
| 3 | Public versus Private Inheritance | `UNIT 2/Program_03` | Shows how `Base::show()` remains publicly accessible through public inheritance but becomes inaccessible from outside the class through private inheritance. |
| 4 | Multilevel Inheritance | `UNIT 2/Program_04` | Demonstrates a three-level chain `Person -> Employee -> Manager`, where `Manager` displays data inherited from both its parent and grandparent classes. |
| 5 | Hierarchical Inheritance | `UNIT 2/Program_05` | A single `Vehicle` base class is inherited by two separate derived classes, `Car` and `Bike`, each adding its own specific behaviour. |
| 6 | Multiple Inheritance | `UNIT 2/Program_06` | A `Student` class inherits from two base classes, `Academic` and `Sports`, and combines marks from both to compute a total. |
| 7 | Resolving Multiple-Inheritance Ambiguity | `UNIT 2/Program_07` | `Academic` and `Sports` both define a `display()` function; the scope resolution operator (`::`) is used to call the correct version from each base. |
| 8 | Constructor and Destructor Order | `UNIT 2/Program_08` | Shows that base class constructors run before derived class constructors, and destructors run in the reverse order. |
| 9 | Parameterized Base Constructor | `UNIT 2/Program_09` | A `Student` derived class passes a constructor argument up to the parameterized constructor of its `Person` base class. |
| 10 | Function Overriding | `UNIT 2/Program_10` | A virtual `move()` function in `Vehicle` is overridden differently by `Car` and `Boat` to demonstrate runtime polymorphism. |
| 11 | Abstract Class | `UNIT 2/Program_11` | An abstract `Shape` class declares a pure virtual `area()` function, implemented separately by `Rectangle` and `Circle`. |
| 12 | Virtual Base Class and Diamond Inheritance | `UNIT 2/Program_12` | `Student` and `Employee` both virtually inherit from `Person` so that `TeachingAssistant`, which inherits from both, has only one copy of `Person`. |
| 13 | Friend Class | `UNIT 2/Program_13` | The `Auditor` class is declared a friend of `Account`, allowing it to directly access the private `balance` member. |
| 14 | Nested Class | `UNIT 2/Program_14` | A `Department` class is defined inside a `University` class to show how nested classes are declared and used. |
| 15 | Mini-Project - Vehicle Rental System | `UNIT 2/Program_15` | A polymorphic rental billing system where `Car` and `Bike` derive from `Vehicle` and override rent calculation and display logic. |
| 16 | Mini-Project - Employee Payroll System | `UNIT 2/Program_16` | An abstract `Employee` class is extended by `PermanentEmployee` and `ContractEmployee`, each implementing its own salary calculation, demonstrated through a common `displayPaySlip()` function. |



## Unit III: Polymorphism

### List of Programs

| # | Title | Folder | Main Concept | Description |
|---|-------|--------|--------------|-------------|
| 1 | Function Overloading | `UNIT 3/Program_01` | Compile-time polymorphism | Three `add()` overloads demonstrate how the compiler statically resolves function calls based on parameter types and counts. |
| 2 | Area Calculator | `UNIT 3/Program_02` | Overloading with varied parameters | Three `calculateArea()` overloads compute areas for square, rectangle, and circle based on arguments provided. |
| 3 | Unary Minus Operator | `UNIT 3/Program_03` | Unary operator overloading | The `Number` class overloads unary `-` so that `-number` returns a new object with the negated value. |
| 4 | Prefix & Postfix Increment | `UNIT 3/Program_04` | Unary operator overloading | The `Counter` class implements both `++counter` (prefix) and `counter++` (postfix, distinguished by dummy `int`). |
| 5 | Complex Number Addition | `UNIT 3/Program_05` | Binary `+` operator overloading | Overloads binary `+` as a member function to add real and imaginary components of two complex numbers directly. |
| 6 | Distance Comparison | `UNIT 3/Program_06` | Relational operator overloading | The `Distance` class overloads `>` to enable natural relational comparison between two distance objects. |
| 7 | Non-Member / Friend Operator | `UNIT 3/Program_07` | Friend operator overloading | A friend `operator+(int, const Complex&)` allows algebraic expressions where the left-hand operand is a primitive type (`10 + c`). |
| 8 | Base Pointer Without Virtual Function | `UNIT 3/Program_08` | Static (early) binding | A `Base*` pointing to a `Derived` object calls `Base::display()`, illustrating compile-time static binding when functions lack `virtual`. |
| 9 | Base Pointer With Virtual Function | `UNIT 3/Program_09` | Runtime polymorphism | An `Animal*` pointer calls the overridden `sound()` method of the actual runtime object (`Dog`, `Cat`) via dynamic dispatch. |
| 10 | Base Reference With Virtual Function | `UNIT 3/Program_10` | Dynamic binding via references | Passing objects by `const Shape&` preserves the derived runtime type, invoking the correct `area()` without object slicing. |
| 11 | Abstract Class & Pure Virtual Function | `UNIT 3/Program_11` | Abstract interfaces | `Shape` defines `area()` as pure virtual (`= 0`), preventing instantiation and requiring derived classes (`Rectangle`) to implement it. |
| 12 | Collection of Shape Pointers | `UNIT 3/Program_12` | Polymorphic container processing | Uses `std::vector<std::unique_ptr<Shape>>` to store diverse shapes and invoke `displayName()` and `area()` dynamically in a loop. |
| 13 | Virtual Destructor | `UNIT 3/Program_13` | Safe dynamic deallocation | Demonstrates that declaring `virtual ~Base()` ensures `delete` through a base pointer properly calls derived and base destructors. |
| 14 | Object Slicing Demonstration | `UNIT 3/Program_14` | Object slicing vs. references | Demonstrates how passing by value slices away derived members and vtable, whereas passing by reference preserves full polymorphic behavior. |
| 15 | Payment Processing System | `UNIT 3/Program_15` | Real-world polymorphic interface | An abstract `Payment` interface is implemented by `CardPayment`, `UpiPayment`, and `NetBankingPayment`, processed via a unified handler. |
| 16 | Employee Payroll Mini-Project | `UNIT 3/Program_16` | Integrated polymorphism project | An abstract `Employee` base class is extended by `PermanentEmployee` and `ContractEmployee`, each calculating salary polymorphically for pay slips. |


