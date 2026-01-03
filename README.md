# 📚 RUET Student Management System

*A Complete OOP-Based Academic Management Platform*

A modern, web-based **Student Management System** demonstrating **Object-Oriented Programming (OOP)** principles — built as a course project for **RUET CSE 2K21 Batch (ECE '23 OOP Course)**.

This system simulates a real-world university management portal with **role-based dashboards** for **Students, Teachers, and Administrators**.

---

## ✨ Key Features

### 🔐 Role-Based Access

✔ **Student Portal** – course registration, grades, CGPA
✔ **Teacher Portal** – grading & student progress
✔ **Admin Dashboard** – user management & analytics

---

## 🛠️ OOP Concepts Implemented

| Concept            | Implementation                                          | Location    |
| ------------------ | ------------------------------------------------------- | ----------- |
| Classes & Objects  | User, Student, Teacher, Admin classes                   | All         |
| Inheritance        | Hierarchical inheritance (User → Student/Teacher/Admin) | script.js   |
| Polymorphism       | Method overriding                                       | script.js   |
| Encapsulation      | Private members & getters/setters                       | script.js   |
| Abstraction        | Abstract User base class                                | script.js   |
| Templates          | Generic functions                                       | C++ backend |
| Exception Handling | Safe input validation                                   | C++ backend |
| File Handling      | CSV persistence                                         | C++ backend |
| Diamond Problem    | Virtual inheritance                                     | C++ backend |
| Static Members     | Global user tracking                                    | C++ backend |

---

## 🎨 Modern UI Highlights

* Responsive (Mobile + Desktop)
* Smooth animations
* Interactive dashboards
* Real-time statistics
* Department badge colors
* Clean, minimal design

---

## 🚀 Quick Start

### **Requirements**

* Any modern browser
* Text editor (VS Code recommended)
* *(Optional)* VS Code Live Server

### **Install**

1. Download / Clone project
2. Create folder `student-management-system`
3. Add:

   * `index.html`
   * `style.css`
   * `script.js`
4. Open `index.html`

✔ Done!

---

## 👥 Demo Users

### 🎓 Student

```
ID: 2310047
Name: Mustakim Al Siyam
Department: ECE
Semester: 3
```

### 👨‍🏫 Teacher

```
ID: 100
Name: Dr. Kim Jung
Department: CSE
```

### ⚡ Admin

```
ID: 999
Name: Super Admin
```

---

## 📁 Project Structure

```
student-management-system/
├── index.html
├── style.css
├── script.js
└── backend/
    ├── main.cpp
    └── *.csv
```

---

## 🎮 How It Works

### Students Can:

✔ Register Courses
✔ View Grades
✔ Calculate CGPA
✔ Update Profile

### Teachers Can:

✔ View Students
✔ Assign Grades
✔ Track Progress

### Admins Can:

✔ Create Users
✔ Monitor System
✔ Export Data

---

## 🔧 Tech Stack

**Frontend**

* HTML5
* CSS3 (Flexbox + Grid + Animations)
* JavaScript (ES6, localStorage)

**Backend (Optional Module)**

* C++
* File I/O
* OOP

---

## 📊 Example Student Data

```js
{
  id: 2310047,
  name: "Mustakim Al Siyam",
  department: "ECE",
  semester: 3,
  registered: false,
  marks: [-1, -1, -1, -1, -1],
  credits: [3,3,3,3,3]
}
```

---

## 🛠 Customization Guide

✔ Add departments
✔ Change semesters
✔ Add new features
✔ Style UI

Everything is modular & easy to extend.

---

## 🎯 Learning Outcomes

### **OOP Concepts**

* Abstraction
* Encapsulation
* Inheritance
* Polymorphism
* Reusability
* Exception Handling
* File Persistence

### **Web Dev Skills**

* Responsive UI
* DOM manipulation
* Forms & validation
* LocalStorage
* Animations

---

## 📈 Performance

✔ Works Offline
✔ Zero Dependencies
✔ Fast Load
✔ Mobile Friendly

---

## 🐛 Troubleshooting

| Issue               | Fix                |
| ------------------- | ------------------ |
| Page blank          | Check console      |
| Login fails         | Clear localStorage |
| CSS broken          | Verify links       |
| Buttons not working | Check JS errors    |

Useful debug:

```js
console.log(systemData);
localStorage.clear();
```

---

## 🔮 Future Enhancements

* Real backend API
* Database support
* Auth system
* Analytics dashboard
* Attendance module
* Dynamic course management

---

## 🤝 Contributing

1. Fork repo
2. Create branch
3. Commit
4. Push
5. Open PR

---

## 📜 License

Educational project — RUET ECE’23 OOP Course.

---

❤️ Built for RUET ECE'23 — OOP Course Project

---
