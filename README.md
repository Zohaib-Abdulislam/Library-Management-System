# 📚 Library Management System

A robust, desktop-based **Library Management System** built using **Java Swing**. This project is specifically engineered to demonstrate advanced object-oriented programming concepts, strict input validation, and the implementation of a custom exception-handling architecture.

---

## 📂 Project Structure

All core logic and interface components are located within the `src` directory:

| File | Type | Description |
| :--- | :--- | :--- |
| `LibraryManagementSystem.java` | Main Driver | Handles the GUI layout, event listeners, and core application workflow. |
| `EmptyFieldException.java` | Custom Exception | Intercepts submissions where required text inputs are left blank. |
| `InvalidRollNumberException.java` | Custom Exception | Enforces strict formatting rules for student/user Roll Numbers. |
| `InvalidDateException.java` | Custom Exception | Validates date inputs to ensure chronological accuracy and proper formatting. |
| `NullSelectionException.java` | Custom Exception | Triggers if a user skips a mandatory ComboBox or Radio Button selection. |

---

## ⚡ Core Features

*   **Swing-Driven Graphical User Interface:** A clean, component-rich desktop application utilizing `JTextField`, `JComboBox`, `JRadioButton`, and `JTextArea` for seamless user interaction.
*   **Custom Exception Architecture:** Moves beyond native Java exceptions by implementing tailored, domain-specific exception classes to handle strict business rules.
*   **Robust Data Validation Flow:** Utilizes precise `try-catch-throw-finally` blocks to intercept faulty user inputs, safely reset resources, and prevent runtime application crashes.
*   **Instant User Feedback:** Integrates `JOptionPane` alert dialogs to provide real-time, context-specific error prompts or successful transaction confirmations.

---

## 🛠️ Installation & Running the Application

### Prerequisites
*   **Java Development Kit (JDK)** (Version 8 or higher recommended)
*   A terminal, command prompt, or any standard Java IDE (Eclipse, IntelliJ IDEA, NetBeans)

### Execution Steps
To compile and run the application manually via the CLI, execute the following commands:

```bash
# Clone the repository (if downloading via git)
git clone [https://github.com/yourusername/library-management-system.git](https://github.com/yourusername/library-management-system.git)

# Navigate to the source directory
cd library-management-system/src

# Compile all Java source files simultaneously
javac *.java

# Execute the main application driver
java LibraryManagementSystem
