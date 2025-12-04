# ✅ TaskFlow – Official Task Management System

TaskFlow is a modern, lightweight, and fully client-side **task management system** built with **HTML, Tailwind CSS, jQuery, and LocalStorage**. It is designed for daily productivity tracking with powerful filtering, priority management, dark mode, printing, and real-time progress tracking.

---

## 🖼 Preview

![TaskFlow Preview](https://github.com/iammazharul/TaskFlow/blob/2bedf8fc9765fd712774aa2d9cb82796ebf23d4d/screenshot/screenshot-v3.png)

> Live preview showcasing dark mode, filtering, priorities, progress tracking, and task registry.

---

## 🚀 Features

### ✅ Core Task Management
- Add, edit, delete, and complete tasks
- Instant task saving with LocalStorage
- Inline task editing
- Task timestamps and creation date

### 🎯 Priority & Categories
- Priority levels: **Low, Medium, High**
- Categories: **Work, Personal, Health, Other**
- Priority color indicators & icons

### 🔍 Smart Filters & Search
- Filter by:
  - All Tasks
  - Active Tasks
  - Completed Tasks
  - High Priority
- Category-based filtering
- Live search by task name

### 📊 Productivity Dashboard
- Total tasks counter
- Completed tasks counter
- Pending tasks counter
- High-priority task counter
- Automatic daily progress bar calculation

### 🌙 Dark Mode
- One-click dark mode toggle
- Theme preference saved in browser

### 🖨 Print Support
- Print-friendly layout
- Clean printable task report
- Automatically hides UI controls on print

### ⚡ UI Enhancements
- Smooth animations
- Loading indicator while adding tasks
- Task delete fade-out animation
- Focus pulse animation for active input

### ⌨ Keyboard Shortcuts
| Shortcut | Action |
|----------|--------|
| `Alt + N` | New Task |
| `Alt + F` | Search |
| `Alt + D` | Toggle Dark Mode |

### 🧠 Smart Sorting
- Sort by:
  - Created Time
  - Priority
  - Task Time

---

## 🛠 Tech Stack

- **HTML5**
- **Tailwind CSS**
- **jQuery 3.7.1**
- **Font Awesome 6.4**
- **LocalStorage API**

---

## 📂 Project Structure

```

/project-root
│── index.html
│── /screenshots
│     └── screenshot-v2.png
│── README.md

````

---

## 📦 Installation & Usage

### 1️⃣ Clone Repository
```bash
git clone https://github.com/your-username/taskflow.git
````

### 2️⃣ Open the App

Simply open `index.html` in your browser:

```bash
open index.html
```

✅ No server
✅ No database
✅ No installation required

---

## 💾 Data Storage

All tasks are stored securely inside the browser using:

* `localStorage.getItem('dailyTasks')`
* `localStorage.getItem('darkMode')`

⚠️ Clearing browser storage will remove tasks.

---

## 📌 Version Info

* **Version:** `1.0.0`
* **Release Type:** Official Stable Release
* **License:** MIT

---

## 🧩 Roadmap (Upcoming Features)

* ✅ Task export to PDF
* ✅ Multi-day task history
* ✅ Cloud sync (Firebase optional)
* ✅ User login system
* ✅ Mobile app wrapper (Flutter / PWA)

---

## 👨‍💻 Author

**TaskFlow Management System**
Developed by **Mazharul Islam**

---

## ⭐ Support & Contribution

If you like this project:

✅ Give it a star
✅ Fork it
✅ Improve it
✅ Share it

Pull requests and feature requests are welcome!

---

## 📜 License

This project is licensed under the **MIT License** – feel free to use it for commercial and personal projects.

```

---