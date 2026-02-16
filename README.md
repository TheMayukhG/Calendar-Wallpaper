# Study Tracker Pro — Lively Wallpaper App

## Overview

**Study Tracker Pro** is an interactive browser-based productivity wallpaper designed for use with Lively Wallpaper. It combines a minimal calendar interface, exam tracking, and progress visualization into a single lightweight HTML application that runs directly as a desktop wallpaper.

The application helps users maintain study discipline, track upcoming exams or milestones, and visualize daily progress without disrupting their workspace.

This project demonstrates UI architecture, local persistence design, and interactive state-driven rendering using vanilla web technologies.

---

## Features

* **Interactive Calendar**

  * Cross off completed study days
  * Mark target dates (e.g., exams or deadlines)
  * Visual indicators for past, present, and upcoming events

* **Target Management**

  * Add labeled targets with color customization
  * Pastel or raw color selection
  * Countdown information card on double-click

* **Study Streak Tracking**

  * Automatic streak calculation based on consecutive crossed days

* **Timeline Visualization**

  * Chronological view of upcoming targets
  * Gap analysis between milestones
  * Progress bars showing completion ratios

* **Configuration Backup**

  * Export configuration as JSON
  * Import previous configurations
  * Clipboard copy and file download support

* **Local Persistence**

  * State stored in browser localStorage
  * No external dependencies or backend required

---

## Technology Stack

* HTML5
* CSS3
* Vanilla JavaScript
* Browser Local Storage API

No frameworks or third-party libraries are used.

---

## Setup & Usage with Lively Wallpaper

### Requirements

* Windows system
* Installed copy of **Lively Wallpaper**

### Adding the Wallpaper

1. Launch Lively Wallpaper.
2. Click **Add Wallpaper**.
3. Choose **Browse**.
4. Select the provided HTML file (`index.html` or project file).
5. Confirm the selection.
6. Click the wallpaper thumbnail in the library to activate it.

The application will now run interactively on your desktop background.

---

### Recommended Settings (Optional)

For optimal responsiveness:

* Enable interaction forwarding in Lively settings.
* Set wallpaper scaling to **Fit** or **Fill** depending on display ratio.
* Avoid clearing browser cache or wallpaper data unless you intend to reset progress.

---

### Basic Controls

| Action              | Description                 |
| ------------------- | --------------------------- |
| Click (Cross Mode)  | Toggle study day completion |
| Click (Target Mode) | Add or remove target        |
| Double Click Target | Open countdown information  |
| Menu Button         | Import/Export configuration |
| View Timeline       | Switch visualization mode   |

---

## Project Structure

Single-file implementation:

* `index.html`

  * UI layout
  * Styling
  * Application logic
  * State management

The architecture is intentionally self-contained for portability and seamless deployment within wallpaper environments.

---

## Design Goals

* Minimal distraction interface suitable for background usage
* Immediate visual feedback
* Lightweight runtime footprint
* Offline-first operation
* Clean modular organization within a single-page structure

---

## Limitations

* Desktop-focused interaction model
* Data stored locally (clearing cache removes progress)
* No cloud synchronization

---

## License

This project is provided for portfolio demonstration purposes.
Usage or modification permissions may be defined by the repository owner.

---

## Author

Mayukh Saha

Portfolio submission project demonstrating UI/UX design, front-end architecture, and state-driven interactivity.
