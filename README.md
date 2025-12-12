# Kanban Board

A simple, clean, and functional Kanban Board built using HTML, CSS, and Vanilla JavaScript.  
It allows you to create tasks, drag & drop them across columns, delete tasks, and automatically saves everything using LocalStorage.

---

## 🚀 Features

### ✔ Add New Tasks  
Create tasks with a title and description using a modal form.

### ✔ Drag & Drop  
Move tasks seamlessly between To Do, In Progress, and Done columns.

### ✔ Delete Tasks  
Each task has a delete button to remove it instantly.

### ✔ Persistent Storage  
All tasks are saved to LocalStorage, so your board stays intact even after refreshing.

### ✔ Automatic Task Count  
Each column shows the number of tasks inside it and updates in real time.

---

## 🧩 Tech Stack

- HTML5  
- CSS3  
- JavaScript (Vanilla)

---

## 📂 Project Structure
/
├── index.html # Main UI layout
├── style.css # Styling (theme, layout, modal, tasks)
└── index.js # App logic (task management, drag & drop, localStorage)

---

## ⚙️ How It Works

### ➤ 1. Adding a Task
The modal collects a title and description, then calls:

`addTask(taskTitle, taskDescription, todo);`

### ➤ 2. Drag & Drop
Each task is draggable and can be moved into any column.

### ➤ 3. Delete Button
Every task includes a delete button that removes it and updates counts.

### ➤ 4. LocalStorage Sync
Tasks are saved after every change using:

`localStorage.setItem("tasks", JSON.stringify(taskData));`

---

## 🛠 Future Improvements

- Edit task feature  
- Priority labels  
- Due dates  
- Dark/light theme switch  
- Search tasks  
- Custom categories  

---

## 👩‍💻 Author

Built with ❤️ by **Poshak**.  
If you use this project, feel free to star ⭐ the repo!

---

## 📄 License

This project is free to use. Add a license if you publish on GitHub.

