# Student_Management_System
# 📘 Student Management System (Java)

This project is a simple **Student Management System** developed in **Java** that allows users to manage student records using a menu-driven console interface. It demonstrates core object-oriented programming (OOP) concepts including:

- Inheritance
- Method Overloading and Overriding
- Constructor Overloading
- Arrays
- Interfaces
- Console-based input/output

---

## 🧠 Key Concepts Demonstrated

### ✅ Inheritance
- The `Student` class **inherits** from the `Person` base class.

### ✅ Method Overloading
- `calculateGrade(double marks)`
- `calculateGrade(int theoryMarks, int practicalMarks)`

### ✅ Method Overriding
- The `Student` class overrides the `displayInfo()` method of the `Person` class.

### ✅ Constructor Overloading
- Both `Person` and `Student` classes contain **default and parameterized constructors**.

---

## 🧾 Features

### 1. Add Student
- Input student's name, age, roll number, and marks.

### 2. Display All Students
- Display all stored student details, including calculated grades.

### 3. Calculate Grade (Theory + Practical)
- Enter theory and practical marks to calculate the average and corresponding grade.

### 4. Exit
- Exit the program.

---

## 🧮 Grading Logic

| Marks Range   | Grade |
|---------------|-------|
| 90 and above  | A     |
| 75 - 89       | B     |
| 60 - 74       | C     |
| 40 - 59       | D     |
| Below 40      | F     |

---

## 🛠️ How to Run

### ✅ Requirements
- Java JDK (8 or above)
- Command Line / Terminal

### 🔧 Steps

1. **Clone the Repository** (or download the `.java` file):
   ```bash
   git clone https://github.com/your-username/StudentManagement.git
   cd StudentManagement
Compile the Program:

javac StudentManagement.java

Run the Program:

java StudentManagement

📸 Sample Output

--- Student Management System ---
1. Add Student
2. Display All Students
3. Calculate Grade with Theory & Practical
4. Exit
Enter your choice: 1

Enter name: John

Enter age: 20

Enter roll number: 101

Enter marks: 87

Student added successfully.

--- Student Management System ---

Enter your choice: 2

Student #1

Name: jhon

Age: 20

Roll No: 101

Marks: 87.0

Grade: B

📂 File Structure

StudentManagement/

├── StudentManagement.java   // Main program file

├── README.md                // Project documentation

👨‍💻 Author
Your Name

GitHub: @manipathak2

Email: manipathak2207@gmail.com

📄 License
This project is licensed under the MIT License.

💡 Future Enhancements
Add support for editing and deleting students.

Save and load data using files.

GUI version using JavaFX or Swing
