# 🎓 Student Management System

The **Student Management System** is a modular, console-based Java application that demonstrates key Object-Oriented Programming (OOP) principles. It provides an interactive environment for admins and students to manage courses, learning materials, and exams.

---

## 📌 Features

### 👨‍🏫 Admin
- Create new courses with title, description, and duration
- Add learning materials to courses
- Add and manage multiple-choice exam questions
- Delete courses if needed

### 👨‍🎓 Student
- Register and log in
- Enroll in available courses
- View course materials
- Attempt multiple-choice exams
- View exam results instantly

---

## 🧱 System Architecture

- **User** (base class)
  - Admin
  - Student
- **Course**: Contains course info, materials, and associated Exam
- **Exam**: Stores questions and handles exam logic
- **Result**: Tracks student performance
- **Main**: The driver class managing program flow

---

## 💡 OOP Concepts Demonstrated
- Inheritance (`Admin`, `Student` → `User`)
- Encapsulation (private fields with getters/setters)
- Abstraction and modular class design

---

## ⚙️ Technology Stack

- **Language**: Java
- **Environment**: IntelliJ IDEA or any Java IDE
- **User Interface**: Console (Scanner-based I/O)
- **Data Storage**: In-memory (Lists, Maps)

---

## 🚀 Future Enhancements
- GUI using JavaFX or Swing
- Persistent storage using files or databases
- Login and session management
- Feedback/comment system
- Reporting & analytics module

---

## 🔧 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/student-management-system.git
Open the project in IntelliJ IDEA or any Java IDE.

Run the Main.java file.

📄 License
This project is open-source and available under the MIT License.

🙋‍♂️ Author
syed mohammad haris

Email: your.syedh9721@example.com
