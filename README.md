# Dev_Tab: The Ultimate Cyberpunk Developer Dashboard

**Dev_Tab** is a feature-rich, high-performance Chrome Extension that replaces your default "New Tab" page with a futuristic, hacker-themed command center. Designed for developers who live in the terminal and breathe productivity.

![License](https://img.shields.io/badge/license-MIT-green)
![Version](https://img.shields.io/badge/version-1.0-blue)

---

## System Overview

Dev_Tab is built to eliminate distractions while providing instant access to the tools you use daily. It features a stunning **Glassmorphism UI** with a dynamic **Matrix background effect**, perfectly optimized for modern workflows.

### Key Features

#### 🛡️ Dual-Mode Dashboard
- **Developer Hub**: Features a LeetCode Daily tracker and a fully functional Cyber Terminal.
- **Focus Mode**: A minimalist layout with a persistence scratchpad and daily motivational quotes to keep you in the zone.

#### Cyber Terminal
A custom terminal emulator built into your browser. Supports commands such as:
- `hash <text>`: Generate SHA-256 hashes instantly.
- `joke`: Get a random programming joke.
- `ip`: Fetch your current public IP address.
- `b64e/b64d`: Base64 encode and decode utility.
- `timer`: Check your current Pomodoro status.

#### Cyber Pomodoro
An integrated Pomodoro timer featuring a custom **SVG Animated Hourglass**. Includes audio alerts and visual cues to manage your sprint sessions effectively.

#### Smart Bookmarking
A custom-built bookmark manager with:
- Drag-and-drop reordering.
- Automatic favicon fetching.
- Quick-add interface for rapid resource saving.

#### Persistent Tasks & Notes
- **To-Do List**: A daily task manager that automatically refreshes each day, keeping only your pending items.
- **Quick Notes**: A persistent scratchpad that saves your thoughts across sessions.

#### Customization Engine
- **Live Theme Engine**: Change the primary neon color of the entire UI in real-time.
- **Adaptive Components**: Toggle visibility of bookmarks, developer hub, or task lists.
- **Personalized Greeting**: Dynamic typing effect greeting based on your set username.

---

## Technical Stack

- **Core**: Vanilla JavaScript (ES6+), HTML5, CSS3.
- **APIs**: Chrome Storage API, Chrome Bookmarks API.
- **External Integrations**: Alfa LeetCode API, DummyJSON Quotes, IPify.
- **Design**: CSS Grid, Flexbox, Glassmorphism, Canvas API (for Matrix effect).

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/devesh-rawat/DevTab.git
   ```
2. Open Chrome and navigate to chrome://extensions/.

3. Enable Developer Mode (toggle in the top right).

4. Click Load unpacked and select the project directory.

5. Open a new tab and start your session.

---

## Contribution
Contributions are welcome! If you have ideas for new terminal commands or UI improvements, feel free to fork the repo and submit a PR.

## 👤 Author
Devesh Rawat
