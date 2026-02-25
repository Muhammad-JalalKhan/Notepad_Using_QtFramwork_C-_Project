# 📝 NotepadQT — Feature-Rich Desktop Text Editor

![Platform](https://img.shields.io/badge/Platform-Windows-blue)
![Language](https://img.shields.io/badge/Language-C%2B%2B-brightgreen)
![Framework](https://img.shields.io/badge/Framework-Qt%206-41CD52?logo=qt)
![IDE](https://img.shields.io/badge/IDE-Qt%20Creator-orange)
![Semester](https://img.shields.io/badge/Semester-3rd-red)
![DSA](https://img.shields.io/badge/Course-DSA-blueviolet)

---

## 📌 Overview

**NotepadQT** is a **cross-platform desktop text editor** built using **C++** and the **Qt Framework**, developed as a **3rd Semester Data Structures & Algorithms (DSA)** semester project. The application demonstrates the practical implementation of DSA concepts — most notably the use of a **Stack data structure** for the Undo feature — wrapped inside a clean, modern, and responsive GUI.

---

## 🖥️ Screenshots

> _Add your application screenshots here_

---

## ✨ Features

- 🏠 **Clean Launch UI** — Minimal and distraction-free editor on startup
- 📂 **File Management** — Create, Open, Save & Save As text files
- ↩️ **Undo Operation** — Stack-based undo for reliable edit history
- ✂️ **Text Operations** — Cut, Copy, Paste & Select All
- 🔤 **Font Customization** — Change font style and size
- 🖥️ **Intuitive GUI** — User-friendly interface built with Qt Widgets
- 🌐 **Cross-Platform** — Compatible with Windows, Linux & macOS

---

## 🧠 DSA Concepts Applied

| Concept | Application |
|---|---|
| **Stack** | Undo operation — tracks edit history using LIFO principle |
| **String Manipulation** | Text processing, search, and formatting |
| **File I/O** | Reading and writing `.txt` documents |
| **Linked Structures** | Managing document state and buffer history |

---

## 🛠️ Technologies Used

| Technology | Details |
|---|---|
| Language | C++ |
| Framework | Qt Framework |
| UI | Qt Widgets |
| IDE | Qt Creator / Visual Studio |
| Build System | qmake / CMake |
| Platform | Windows / Linux / macOS |

---

## 📁 Project Structure

```
NotepadQT/
│
├── main.cpp               # Application entry point
├── mainwindow.h           # Main window header
├── mainwindow.cpp         # Main window logic & event handling
├── mainwindow.ui          # Qt Designer UI layout file
├── NotepadQT.pro          # Qt project file
└── resources/
    └── icons/             # Application icons & assets
```

---

## 🚀 Getting Started

### ✅ Prerequisites
- Windows / Linux / macOS
- Qt Framework 6.x or later
- Qt Creator IDE
- C++17 compatible compiler (MinGW / MSVC / GCC)

### 📦 Installation & Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/Muhammad-JalalKhan/Notepad_Using_QtFramwork_C-_Project.git
   ```

2. **Open in Qt Creator**
   ```
   Open "NotepadQT.pro" in Qt Creator
   ```

3. **Build the Project**
   ```
   Build > Build All  (Ctrl + Shift + B)
   ```

4. **Run the Application**
   ```
   Press F5 or click the Run button (Ctrl + R)
   ```

---

## 🔍 How Undo Works (DSA Concept)

The **Undo feature** is implemented using the **Stack data structure**, following the **LIFO (Last In, First Out)** principle:

```
User Types → State pushed onto Stack
User Presses Undo → Last state popped from Stack → Editor restored
```

> This is a direct real-world application of the **Stack ADT** taught in the DSA course.

---

## 🎓 Academic Context

> **Course:** Data Structures & Algorithms (DSA)
> **Semester:** 3rd Semester
> **Project Type:** Semester Project
> **Concepts Applied:**
> - Stack Data Structure (Undo Feature)
> - Object-Oriented Programming in C++
> - Qt GUI Framework & Event-Driven Programming
> - File Handling & Stream I/O
> - Modular & Component-Based Design

---

## 👨‍💻 Developer

**Muhammad Jalal Khan**
🎓 3rd Semester — Computer Science Student
🔗 [GitHub Profile](https://github.com/Muhammad-JalalKhan)

---

## 📄 License

This project is for **academic purposes only**.

---

⭐ _If you found this project helpful, consider giving it a star!_