

# ⏱️ Modern Stopwatch & Timer

A **modern, responsive Stopwatch and Timer web application** built using **HTML, CSS, and JavaScript**.
This project features a clean glassmorphism UI, smooth interactions, and fully client-side functionality—no external libraries required.

---

## 📌 Project Overview

The **Modern Stopwatch & Timer** is a single-page web application that provides two core time-tracking tools:

* **Stopwatch** – measures elapsed time with lap recording
* **Timer** – counts down from a user-defined duration with alarm notification

The application uses a **tab-based interface** to switch between modes, offering a smooth and intuitive user experience.

---

## ✨ Features

### 🕒 Stopwatch

* Start, pause, and reset functionality
* Displays **minutes, seconds, and centiseconds**
* Lap recording system
* Laps are displayed dynamically in a scrollable list

### ⏲️ Timer

* User input for **minutes and seconds**
* Start, pause, and reset controls
* Countdown display in `MM:SS` format
* Plays an **alarm sound** when time reaches zero
* Supports **device vibration** (on supported devices)

### 🎨 UI & Design

* Modern **glassmorphism design**
* Dark gradient background
* Responsive layout (mobile & desktop friendly)
* Smooth button animations
* Google **Inter** font integration

---

## 🛠️ Technologies Used

| Technology           | Purpose                                 |
| -------------------- | --------------------------------------- |
| **HTML5**            | Structure and layout                    |
| **CSS3**             | Styling, animations, and responsiveness |
| **JavaScript (ES6)** | Application logic and interactivity     |
| **Google Fonts**     | Modern typography                       |
| **Web Audio API**    | Timer alarm sound                       |
| **Vibration API**    | Timer vibration alert                   |

---

## 📂 Project Structure

```
📁 modern-stopwatch-timer
│
├── index.html   # Main application file (HTML, CSS, JS combined)
└── README.md    # Project documentation
```

> ⚠️ All styles and scripts are embedded directly in `index.html` for simplicity and easy deployment.

---

## 🚀 How to Run the Project

### Method 1: Open Locally

1. Download or clone the repository
2. Open `index.html` in any modern web browser
3. The application will run instantly

### Method 2: Use Live Server (Recommended)

1. Open the project folder in **VS Code**
2. Install the **Live Server** extension
3. Right-click `index.html` → **Open with Live Server**

---

## 🧠 How It Works

### Stopwatch Logic

* Uses `setInterval()` running every **10 milliseconds**
* Time is stored in milliseconds
* Formatted as `MM:SS:CS`
* Laps are stored dynamically using DOM manipulation

### Timer Logic

* Converts user input into total seconds
* Decrements time every second using `setInterval()`
* Triggers:

  * Alarm sound
  * Device vibration (if supported)
* Automatically stops when time reaches zero

---

## 📱 Browser Compatibility

| Browser         | Status                                |
| --------------- | ------------------------------------- |
| Chrome          | ✅ Fully Supported                     |
| Edge            | ✅ Fully Supported                     |
| Firefox         | ✅ Fully Supported                     |
| Safari          | ⚠️ Alarm may require user interaction |
| Mobile Browsers | ✅ Responsive & Vibration Supported    |

---

## 🔊 External Resources Used

* **Alarm Sound**
  Source: Google Actions Sound Library

  ```
  https://actions.google.com/sounds/v1/alarms/alarm_clock.ogg
  ```

---

## 📸 Screens & UI Highlights

* Tab-based navigation between Stopwatch and Timer
* Centered large time display
* Soft shadows and blurred background
* Clear button hierarchy (Primary / Secondary)

---

## 🎯 Possible Improvements (Future Enhancements)

* Save laps and timer history using `localStorage`
* Add dark/light theme toggle
* Custom alarm sound selection
* Fullscreen / PWA support
* Multiple timers support

---

## 👨‍💻 Author

**Jeremy Eclarino**
Built as part of a **JavaScript UI & functionality project**
Ideal for:

* Academic submissions
* UI/UX demos
* Frontend portfolios

---

## 📄 License

This project is **open for educational and personal use**.
You may modify and reuse it freely with proper credit.

