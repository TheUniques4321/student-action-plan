# Student Action Plan Dashboard

A responsive dashboard hosted on **GitHub Pages** that connects to Google Apps Script and Google Sheets to dynamically fetch and display real-time tasks for students.

## 🚀 Live Demo
- **Default Dashboard**: [https://jragbir1.github.io/student-action-plan/](https://jragbir1.github.io/student-action-plan/)
- **Filter by Student URL**: `https://jragbir1.github.io/student-action-plan/?student=PETER`

## ✨ Features
- **Real-time Synchronization**: Pulls live action items directly from Google Sheets via Google Apps Script Web App.
- **Dynamic Student Switching**: Switch between students using the UI search box or via URL query parameters (`?student=STUDENT_NAME`).
- **Status & Blockers**: Displays project names, due dates, action status, and "Waiting on" blockers.
- **Responsive Design**: Optimized for mobile and desktop screens.

## 🛠️ Configuration
Backend Web App endpoint:
```javascript
const SCRIPT_URL = "https://script.google.com/macros/s/AKfycbwRDqgOWTpGLO8MRGgvB6d5CIa89ZIEttgDLfucXWA6j-hewSFDFyAyJo9b6_X-KB_1-g/exec";
```
