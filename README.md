
# 📘 Student Management System (Java)

A simple Java console application that demonstrates **inheritance**, **interfaces**, **method overloading/overriding**, and **polymorphism**, based on the assignment requirements.

---

## 📌 Features

### ✔ Add Student

Enter roll number, name, email, course, and marks.

### ✔ Delete Student

Removes a student by roll number.

### ✔ Update Student

Edits an existing student record.

### ✔ Search Student

Displays details of a single student.

### ✔ View All Students

Shows all stored student records.

### ✔ Grade Calculation

Grades are assigned automatically based on marks:

* **A** → 90+
* **B** → 75–89
* **C** → 60–74
* **D** → <60

---

## 🧰 Concepts Used

* **Abstract Class (Person)**
* **Inheritance (Student extends Person)**
* **Interface (RecordActions)**
* **Polymorphism (Dynamic Method Dispatch)**
* **Method Overloading and Overriding**
* **HashMap** for efficient student storage

---

## 📂 File Structure

```
Person.java
Student.java
RecordActions.java
StudentManager.java
MainApp.java
```

---

## ▶️ How to Run

1. Save all `.java` files in the same folder.
2. Open terminal/command prompt inside that folder.
3. Compile all files:

```
javac *.java
```

4. Run the program:

```
java MainApp
```

---

## 📝 Example Output

```
===== Student Management Menu =====
1. Add Student
2. Delete Student
3. Update Student
4. Search Student
5. View All Students
6. Exit
Enter Choice:
```

---

## 🎯 Learning Outcomes

This project helps you understand:

* Class design and object creation
* Inheritance and abstract classes
* Working with interfaces
* Using HashMap for record management
* Implementing polymorphism
* Writing modular, clean Java code

