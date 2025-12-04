# ✅ Tasks – Minimal Daily Task Manager

**Tasks** is a clean, minimalist, and keyboard-driven daily task manager built with  
**HTML, Tailwind CSS, jQuery, and LocalStorage**.  
It focuses on **speed, simplicity, and distraction-free productivity**, inspired by **Japanese design principles**.

---

## 🖼 Preview

![Tasks Preview](https://github.com/iammazharul/TaskFlow/blob/2ef47817a96b45e912c5ffa9e21d08498358003a/screenshot/screenshot-v4.png)

> Shows progress bar, live stats, filters, search, dark mode, and full keyboard navigation.

---

## 🎌 Japanese Design Philosophy

This task manager is built around core Japanese design values for clarity, balance, and efficiency.

### 🧘 Simplicity (簡素)
- Clean, distraction-free interface  
- Only essential features are visible  
- Calm, muted color palette  

### 📐 Precision (精密)
- Perfect spacing and alignment  
- Smooth, intentional animations (0.2–0.3s)  
- Carefully crafted micro-interactions  

### ⚙ Functionality (機能)
- Add, complete, delete, edit, search, filter  
- Instant visual feedback  
- Reliable persistent storage  

### 🔍 Attention to Detail (細部へのこだわり)
- Hover-based delete button visibility  
- Subtle shadows, focus rings, and transitions  
- Progress bar with smooth easing  

### ⚡ Efficiency (効率)
- Fully keyboard-controlled workflow  
- Auto-focus for instant task entry  
- Zero performance-blocking effects  

> Built on the philosophy of **“less is more”** — 100% productivity with zero clutter.

---

## 🚀 Features

### ✅ Core Task Management
- Add new tasks instantly  
- Mark tasks as completed  
- Delete tasks with one click  
- Inline task editing using keyboard (`Enter`)  
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

---

## ⌨ Full Keyboard Control

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

---

## 🧼 Clean Shortcuts UI (Minimal Look Preserved)

- ❌ No visible shortcuts panel in the main UI  
- ✅ Shortcuts are accessible via:
  - Pressing **`?`**
  - Clicking the **floating help button**

### Shortcuts Modal
- Smooth fade animation  
- Close with `Esc`, click outside, or close button  
- Fully supports **dark mode**  
- Clean grid layout for key–action pairs  

This keeps the interface **pure, distraction-free, and professional**.

---

## 🖥 UI & UX Enhancements
- Smooth fade-in animations  
- Hover-based delete button visibility  
- Subtle shadows & transitions  
- Japanese-inspired minimalist design  
- Fully responsive layout  
- Focus ring accessibility  

---

## 🔐 Security
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

```txt
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
```

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

⚠️ Clearing browser storage will remove all saved tasks.

---

## 📌 Version Info

* **Version:** `1.0.0`
* **Release Type:** Stable
* **License:** MIT

---

## 🛣 Roadmap

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

This project is licensed under the **MIT License** — free for personal and commercial use.