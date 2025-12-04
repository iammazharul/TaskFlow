Got it — your app has evolved a lot (minimal Japanese-style UI, keyboard-driven, progress tracking). Here is a **fully updated, accurate `README.md`** that matches your **current code exactly**.

You can **replace your existing README.md بالكامل with this**:

---

```md
# ✅ Tasks – Minimal Daily Task Manager

**Tasks** is a clean, minimalist, and keyboard-driven daily task manager built with  
**HTML, Tailwind CSS, jQuery, and LocalStorage**.  
It focuses on **speed, simplicity, and distraction-free productivity** with a Japanese-inspired aesthetic.

---

## 🖼 Preview

![Tasks Preview](./screenshots/screenshot-v2.png)

> Shows progress bar, live stats, filters, search, dark mode, and keyboard navigation.

---

## 🚀 Features

### ✅ Core Task Management
- Add new tasks instantly
- Mark tasks as completed
- Delete tasks with one click
- Inline task editing using keyboard (Enter)
- Tasks saved automatically using `localStorage`

### 📊 Live Progress Tracking
- Animated **progress bar**
- Real-time **completion percentage**
- Automatic update on every action

### 📈 Smart Statistics
- **Total Tasks**
- **Completed Tasks**
- **Pending Tasks**

### 🔍 Filtering & Search
- Filter by:
  - All
  - Active
  - Completed
- Real-time task search
- Empty state handling

### 🌙 Dark Mode
- Toggle using keyboard shortcut
- Preference saved in browser

### ⌨ Full Keyboard Control

| Shortcut | Action |
|----------|--------|
| `Alt + N` | Focus new task input |
| `Alt + F` | Focus search |
| `Alt + A` | Show all tasks |
| `Alt + D` | Toggle dark mode |
| `Alt + C` | Clear completed tasks |
| `↑ / ↓` | Navigate tasks |
| `Space` | Toggle selected task |
| `Delete` | Delete selected task |
| `Enter` | Edit selected task |
| `Esc` | Clear search / Close modal |
| `?` | Open shortcuts help |

### 🖥 UI & UX Enhancements
- Smooth fade-in animations
- Hover-based delete button visibility
- Subtle shadows & transitions
- Japanese-inspired minimalist design
- Fully responsive layout
- Focus ring accessibility

### 🔐 Security
- Built-in **HTML escaping** to prevent XSS attacks

---

## 🛠 Tech Stack

- **HTML5** – Structure
- **Tailwind CSS** – UI styling
- **jQuery 3.7.1** – Interactions & state handling
- **Font Awesome 6.4** – Icons
- **LocalStorage API** – Persistent storage

---

## 📂 Project Structure

```

/
├── index.html
├── README.md
└── screenshots/
└── screenshot-v2.png

````

---

## ⚙️ Installation

No backend. No database. No build tools.

### 1️⃣ Clone the repository
```bash
git clone https://github.com/your-username/tasks.git
````

### 2️⃣ Open the app

```bash
open index.html
```

✅ Works offline
✅ Fully client-side
✅ Zero configuration required

---

## 💾 Data Storage

All tasks are stored in the browser using:

* `localStorage.getItem('tasks')`
* `localStorage.getItem('darkMode')`

⚠️ Clearing browser storage will remove saved tasks.

---

## 📌 Version Info

* **Version:** `1.0.0`
* **Release Type:** Stable
* **License:** MIT

---

## 🛣 Roadmap (Optional)

* 🔔 Task reminders & notifications
* ☁ Cloud sync with login
* 📄 Export tasks to PDF
* 📱 PWA & Mobile App version
* 👥 Shared task lists

---

## 👨‍💻 Author

Developed by **Mazharul Islam**
Bangladesh 🇧🇩

---

## ⭐ Support

If you find this useful:

✅ Star the repo
✅ Share it
✅ Fork & improve it

Pull requests are welcome!

---

## 📜 License

This project is licensed under the **MIT License** – free for personal and commercial use.