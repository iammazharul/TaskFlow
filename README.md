# ✅ Tasks – Minimal Daily Task Manager

**Tasks** is a clean, minimalist, and keyboard-driven daily task manager built with  
**HTML, Tailwind CSS, jQuery, and LocalStorage**.  
It emphasizes **speed, simplicity, and distraction-free productivity** with a Japanese-inspired aesthetic.

---

## 🖼 Preview

![Tasks Preview](https://github.com/iammazharul/TaskFlow/blob/563f7ffb44668b4f7c27c829fb8be71e0db15d2c/screenshot/screenshot-v5.png)

> Clean interface, progress bar, live stats, filters, search, dark mode, and full keyboard navigation.

---

## 🚀 Features

### ✅ Core Task Management
- Add tasks instantly
- Complete or undo tasks
- Delete tasks with a click or keyboard
- Inline task editing (Enter key)
- Tasks saved automatically using `localStorage`

### 📊 Live Progress Tracking
- Smooth, animated **progress bar**
- Real-time **completion percentage**
- Updates dynamically on all actions

### 📈 Smart Statistics
- **Total Tasks**
- **Completed Tasks**
- **Pending Tasks**

### 🔍 Filtering & Search
- Filter tasks: All | Active | Completed
- Live search with instant filtering
- Empty state handling

### 🌙 Dark Mode
- Toggle via keyboard or UI
- Preference saved in browser

### ⌨ Full Keyboard Control
- **Alt + N**: Focus new task input  
- **Alt + F**: Focus search field  
- **Alt + A**: Show all tasks  
- **Alt + D**: Toggle dark mode  
- **Alt + C**: Clear all completed tasks (with confirmation)  
- **↑ / ↓**: Navigate tasks  
- **Space**: Toggle selected task  
- **Delete**: Remove selected task  
- **Enter**: Edit selected task inline  
- **Esc**: Clear search or close modal  
- **?**: Open keyboard shortcuts help (modal)  

> All shortcuts provide **visual feedback** with smooth transitions, toast-style hints, and maintain the Japanese minimal aesthetic.

### 🖥 UI & UX Enhancements
- Fade-in animations for tasks
- Hover-based delete button visibility
- Subtle shadows and smooth transitions
- Japanese minimalist design with clean spacing
- Responsive layout with focus ring accessibility

### 🔐 Security
- Built-in **HTML escaping** to prevent XSS attacks

---

## 🛠 Tech Stack

- **HTML5** – Structure  
- **Tailwind CSS** – Styling & layout  
- **jQuery 3.7.1** – Interactions & state  
- **Font Awesome 6.4** – Icons  
- **LocalStorage API** – Persistent storage  

---

## 📂 Project Structure

```

/
├── index.html
├── README.md
└── screenshots/
└── screenshot-v4.png

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

All tasks and preferences are stored in the browser using:

```js
localStorage.getItem('tasks')
localStorage.getItem('darkMode')
```

⚠️ Clearing browser storage will remove saved tasks.

---

## 📜 Version Info

* **Version:** `1.0.0`
* **Release Type:** Stable
* **License:** MIT

---

## 🛣 Roadmap (Optional)

* 🔔 Task reminders & notifications
* ☁ Cloud sync & login
* 📄 Export tasks to PDF
* 📱 PWA / Mobile app version
* 👥 Shared task lists

---

## 👨‍💻 Author

**Mazharul Islam** – Bangladesh 🇧🇩

---

## ⭐ Support

If you enjoy this project:

* Star the repo
* Share it
* Fork & improve it

Pull requests are welcome!

---

## 📜 License

Licensed under the **MIT License** – free for personal and commercial use.
