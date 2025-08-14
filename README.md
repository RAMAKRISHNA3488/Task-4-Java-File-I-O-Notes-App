# 📝 Java Notes App (File I/O)

A simple **text-based Notes Manager** in Java that allows you to **write** and **read** notes using file handling.  
Data is persisted using **FileWriter** and **BufferedReader**.

---

## 🛠 Tools Used
- **Java** (JDK 8+)
- **VS Code** or any Java IDE
- **Terminal / Command Prompt**

---

## 📂 Project Structure
```
NotesApp/
 └── NotesApp.java
```

---

## 🚀 Features
- Add new notes (saved permanently in `notes.txt`)
- View all saved notes
- Simple menu-driven interface
- Uses **FileWriter** (append mode) for writing
- Uses **BufferedReader** for reading

---

## 📥 Setup & Run

1. **Create project folder** and place `NotesApp.java` inside.

2. **Compile the Java file**:
   ```bash
   javac NotesApp.java
   ```

3. **Run the program**:
   ```bash
   java NotesApp
   ```

---

## 📸 Sample Output

### Example Terminal Session:
```
===== Notes App =====
1. Write a new note
2. View all notes
3. Exit
Enter choice: 1
Enter your note: Learn Java File I/O
✅ Note saved successfully!

===== Notes App =====
1. Write a new note
2. View all notes
3. Exit
Enter choice: 2

===== Your Notes =====
📝 Learn Java File I/O
```

---

## 🧠 Concepts Used
- **FileWriter** with append mode
- **FileReader** & **BufferedReader**
- **Scanner** for input
- **Menu-driven CLI**

---

## 📜 License
This project is free to use and modify for educational purposes.
