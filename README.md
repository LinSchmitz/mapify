# 🗺️ Mapify – Workout Tracking Application

Mapify is a modern workout tracking application built with Vanilla JavaScript that allows users to record and visualize running and cycling activities on an interactive map. Users can log workouts by selecting locations directly on the map, while the application automatically stores workout data locally in the browser for future sessions.

Each workout is displayed as a marker on the map and includes activity-specific metrics such as distance, duration, pace, speed, cadence, and elevation gain. The project leverages modern JavaScript architecture, browser APIs, and Object-Oriented Programming (OOP) principles to deliver a smooth and responsive user experience without relying on external frameworks.

Beyond its practical functionality, Mapify serves as a demonstration of advanced JavaScript concepts, including OOP, state management, browser APIs, and persistent client-side storage.

---

## 🚀 [Live Demo](#)

---

## 📸 Screenshots

## ![Photos](map.png)

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
mapify/
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
git clone https://github.com/yourusername/mapify.git
```

### Navigate to Project

```bash
cd mapify
```

### Run Application

Use VS Code Live Server or any local server:

```bash
npx serve
```

---

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
