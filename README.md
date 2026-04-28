# 💎 Glassmorphism Task Tracker

A sleek, high-performance Task Management application built with a modern "frosted glass" aesthetic. This project demonstrates responsive design, efficient DOM manipulation, and browser-based data persistence.

## 🚀 Live Demo
https://vineeth01006.github.io/task-tracker/

## ✨ Key Features
* **Modern Glassmorphism UI:** Implements multi-layered radial gradients, backdrop filters (`blur`), and semi-transparent borders for a premium look.
* **Real-time Statistics:** Instant tracking of Total, Active, and Completed tasks.
* **Local Persistence:** Uses `localStorage` to ensure your data remains intact even after closing the browser or refreshing the page.
* **Responsive Architecture:** Optimized for all screen sizes using CSS Grid and Flexbox with specific mobile-first breakpoints.
* **Sanitized Inputs:** Includes HTML escaping logic to prevent basic XSS (Cross-Site Scripting) vulnerabilities.

## 🛠️ Tech Stack
* **HTML5:** Semantic structure for accessibility.
* **CSS3:** Custom properties (CSS variables), animations, and advanced filter effects.
* **JavaScript (ES6+):** Vanilla JS for state management and UI updates (No external libraries like React or jQuery required).

## 📂 Project Structure
This is a **Single-File Application (SFA)**.
- `index.html`: Contains the core structure, CSS styling for the glass effect, and the functional logic for task management.

## 📝 How to Use
1.  **Add Task:** Type your task in the input field and click "Add Task" or press Enter.
2.  **Complete Task:** Tap the circular check icon on the left of any task.
3.  **Delete:** Use the "Delete" button to remove a single entry.
4.  **Bulk Action:** Use "Clear Completed" to remove all finished tasks at once.

---
*Created as a high-level exploration of modern CSS and Vanilla JavaScript.*
