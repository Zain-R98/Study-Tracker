# Study Tracker 📄

A lightweight, clean productivity web application having a customizable **Focus Timer** and a **Task Manager** with full local storage persistence and Light/Dark mode support.

## ✨ Features

* **Customizable Focus Timer:**
  * Quick preset duration buttons (15 min, 25 min, 45 min, 60 min).
  * Input field for any study block duration (1 to 180 minutes).
  * Real-time countdown display with start, pause, and reset controls.
* **Session Analytics:**
  * Tracks total completed study sessions and total accumulated study minutes.
  * Dynamically updates stats based on your configured session durations.
  * Automatically saves study stats, active timer preferences, and theme settings to `localStorage`.
* **Subject-Tagged Task Manager:**
  * Add study goals categorized by subject (*Computer Science*, *Mathematics*, *IELTS Prep*, *General*).
  * Interactive checkboxes to complete/uncomplete tasks with strikethrough styling.
  * Delete individual tasks cleanly.
* **Dark & Light Mode:**
  * Clean, responsive CSS variable theme toggling saved across sessions.


## Project Structure

```text
study-tracker/
├── index.html    # Application structure and core logic
├── styles.css    # Clean CSS custom properties & theme styles
└── README.md     # Project documentation
```

## 🚀 Getting Started

### Running Locally

1. Clone or download this repository:
   ```bash
   git clone https://github.com/Zain-R98/Study-Tracker.git
   ```
2. Open `index.html` directly in any web browser. No external dependencies, server setup, or build tools required.

### Usage

1. **Setting Up a Session:** Select a preset focus duration or type a custom duration in minutes, then click **Start**.
2. **Managing Tasks:** Type your study goal in the task box, select a subject tag, and click **Add Task**. Click the checkbox next to any task to mark it as completed.
3. **Toggling Themes:** Click the **🌙 Dark Mode / ☀️ Light Mode** button in the top header to switch themes at any time.

## License

This project is open-source and available under the [MIT License](LICENSE).
