# 📚 Student Record Management System (Java)

## 🎯 Objective
This project is a CLI-based CRUD (Create, Read, Update, Delete) system to manage student records using Java.

---

## 🛠 Technologies Used
- Java
- ArrayList (Collections Framework)
- VS Code / IntelliJ

---

## 🚀 Features
- Add Student
- View Students
- Update Student Details
- Delete Student Record
- Menu-driven CLI interface

---

## 📦 Project Structure
- `Student` class → Stores student details (ID, Name, Marks)
- `StudentManagementSystem` → Main logic and menu

---

## 🔑 Concepts Used
- Classes & Objects
- Encapsulation (Getters & Setters)
- ArrayList (Dynamic Storage)
- Loops & Conditional Statements

---

## ▶️ How to Run

1. Open project in IntelliJ IDEA
2. Compile and run `StudentManagementSystem.java`
3. Follow the menu options in the console

## Sample Output

===== Student Record Management =====
1. Add Student
2. View Students
3. Update Student
4. Delete Student
5. Exit
Enter choice: 1

Enter ID: 101
Enter Name: Raju
Enter Marks: 85
Student Added Successfully!

===== Student Record Management =====
Enter choice: 1

Enter ID: 102
Enter Name: Ravi
Enter Marks: 90
Student Added Successfully!

===== Student Record Management =====
Enter choice: 2

ID: 101, Name: Raju, Marks: 85.0
ID: 102, Name: Ravi, Marks: 90.0

===== Student Record Management =====
Enter choice: 3

Enter Student ID to update: 101
Enter New Name: Rajiv
Enter New Marks: 88
Student Updated!

===== Student Record Management =====
Enter choice: 2

ID: 101, Name: Rajiv, Marks: 88.0
ID: 102, Name: Ravi, Marks: 90.0

===== Student Record Management =====
Enter choice: 4

Enter Student ID to delete: 102
Student Deleted!

===== Student Record Management =====
Enter choice: 2

ID: 101, Name: Rajiv, Marks: 88.0

===== Student Record Management =====
Enter choice: 5

Exiting...
