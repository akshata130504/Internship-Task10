# Internship-Task10

# Java Developer Internship – Task 10  
## Exception Handling & Custom Exceptions


## 📌 Task Objective
The objective of this task is to build a **robust, exception-safe Java application** that demonstrates proper handling of runtime and checked exceptions.  
This task focuses on using `try-catch-finally`, creating and throwing **custom exceptions**, and providing meaningful error messages.

## 🛠 Tools Used
- **IDE:** IntelliJ IDEA / Eclipse  
- **Language:** Java  
- **JDK Version:** Java 17 / Java 21  


## 📂 Project Structure
Java-Internship-Task-10
│
├── src
│ ├── InsufficientBalanceException.java
│ └── ExceptionDemoApp.java
│
└── README.md


## 🧩 Features Implemented
- Identified and handled **runtime exceptions**
- Used **try–catch–finally** blocks
- Created a **custom checked exception**
- Threw exceptions manually using `throw`
- Declared exceptions using `throws`
- Demonstrated **checked vs unchecked exceptions**
- Added **meaningful error messages**
- Logged exceptions using console output


## ▶️ How to Compile and Run
Open terminal / command prompt in the `src` directory and run:

    ```bash
    javac InsufficientBalanceException.java ExceptionDemoApp.java
    java ExceptionDemoApp
    
## 💻 Sample Console Output

Case 1: Insufficient Balance (Custom Exception)

Current Balance: 5000.0

Enter withdrawal amount: 7000

Custom Exception Caught: Insufficient balance. Available balance: 5000.0

Transaction process completed.

Case 2: Invalid Amount (Runtime Exception)

Current Balance: 5000.0

Enter withdrawal amount: -100

Runtime Exception: Withdrawal amount must be positive.

Transaction process completed.

## 🧠 Key Exception Concepts Demonstrated

🔹 Checked vs Unchecked Exceptions

Checked Exception: Must be handled at compile time (Exception)

Unchecked Exception: Occurs at runtime (RuntimeException)

🔹 throw vs throws

throw is used to explicitly throw an exception

throws is used to declare exceptions in method signature

🔹 finally Block

Always executes regardless of exception

Used for cleanup operations like closing resources

🔹 Custom Exception

Represents application-specific or business logic errors

## 🎯 Learning Outcomes

Understood Java exception hierarchy

Learned to create and use custom exceptions

Implemented safe error handling using try-catch-finally

Differentiated between checked and unchecked exceptions

Improved reliability and robustness of Java programs

