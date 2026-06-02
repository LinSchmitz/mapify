# 🗺️ Mapify – Workout Tracking Application

A modern workout tracking application built with Vanilla JavaScript that allows users to record and visualize running and cycling activities on an interactive map.

The project demonstrates advanced JavaScript concepts including Object-Oriented Programming (OOP), browser APIs, state management, and persistent client-side storage.

---

## 🚀 Live Demo

## [Live Demo](#)

## 📷 Photos

## ![Photos](map.png)

## 📌 Overview

Mapty enables users to track outdoor workouts by selecting locations directly on a map and storing workout information locally in the browser.

Each workout is represented by a marker on the map and includes activity-specific metrics such as pace, speed, cadence, and elevation gain.

The application leverages modern JavaScript architecture and browser APIs to provide a smooth user experience without relying on external frameworks.

---

## ✨ Key Features

### 🏃 Running Workouts

- Record running sessions
- Track distance and duration
- Calculate pace automatically
- Store cadence data

### 🚴 Cycling Workouts

- Record cycling sessions
- Track distance and duration
- Calculate average speed
- Store elevation gain

### 🗺️ Interactive Mapping

- Automatic user location detection
- Place workouts directly on the map
- Navigate to workout locations
- Dynamic marker rendering

### 💾 Data Persistence

- Save workouts in Local Storage
- Restore workout history after page refresh
- Maintain workout state across sessions

### 🎯 User Experience

- Instant form validation
- Smooth map navigation
- Responsive layout
- Intuitive workout management

---

## 🛠️ Technologies Used

| Technology        | Purpose           |
| ----------------- | ----------------- |
| HTML5             | Structure         |
| CSS3              | Styling & Layout  |
| JavaScript (ES6+) | Application Logic |
| Leaflet.js        | Interactive Maps  |
| Geolocation API   | User Location     |
| Local Storage API | Data Persistence  |

---

## 🧠 Advanced JavaScript Concepts

This project was built to practice and demonstrate:

- Object-Oriented Programming (OOP)
- ES6 Classes
- Inheritance
- Encapsulation
- Private Fields & Methods
- Event Delegation
- Browser APIs
- State Management
- DOM Manipulation
- Data Validation
- Functional Array Methods

---

## 🏗️ Application Architecture

```text
Workout
├── Running
│   ├── cadence
│   └── pace
│
└── Cycling
    ├── elevationGain
    └── speed
```

### Main Components

- **Workout Class**
  - Base class containing shared workout properties.

- **Running Class**
  - Extends Workout.
  - Calculates running pace.

- **Cycling Class**
  - Extends Workout.
  - Calculates cycling speed.

- **App Class**
  - Handles application state.
  - Manages map interactions.
  - Controls data persistence.
  - Handles UI rendering.

---

## 📂 Project Structure

```text
mapty/
│
├── index.html
├── style.css
├── script.js
├── icons.svg
└── README.md
```

---

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/yourusername/mapty.git
```

### Navigate to Project

```bash
cd mapty
```

### Run Application

Use VS Code Live Server or any local server:

```bash
npx serve
```

---

## 📸 Screenshots

### Main Interface

Add your screenshot here.

```text
screenshots/
├── dashboard.png
├── workout-marker.png
└── mobile-view.png
```

---

## 🔮 Future Enhancements

- Edit existing workouts
- Delete single workouts
- Sort and filter workouts
- Dark mode support
- Export workout data
- Import workout history
- Cloud synchronization
- User authentication
- Backend integration
- Progressive Web App (PWA)

---

## 📈 What I Learned

During this project I gained practical experience with:

- Designing applications using OOP principles
- Working with real-world browser APIs
- Managing application state without frameworks
- Persisting data in the browser
- Building interactive map-based interfaces
- Writing maintainable and modular JavaScript code

---

## 🙏 Acknowledgments

This project was originally inspired by and built while following the JavaScript course by Jonas Schmedtmann, with additional improvements and customization for learning purposes.

---
