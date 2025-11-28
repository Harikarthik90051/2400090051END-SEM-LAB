# React Student Portal Dashboard – Campus Desk

This project is a **Student Portal Dashboard** built with **React (via CDN)** inside a single HTML file.  
It was created for a **Web Technologies / React lab exam** to demonstrate:

- React components
- State management with `useState`
- Conditional rendering for **Login** and **Dashboard**
- UI design with **gradients, cards, shadows, and responsive layout**

---

## 👨‍🎓 Project Overview

The app has two main parts:

1. **Login Screen**
   - Collects **Name**, **Email**, **Password**, and **Role** (Student / Mentor / Admin)
   - Simple validation (checks non-empty fields)
   - On successful login, user is taken to the dashboard

2. **Dashboard Screen**
   - Sidebar navigation (Overview, Courses, Attendance, Results, Calendar, Settings)
   - Top bar with user name, role chip, search box, avatar
   - Statistic cards (CGPA, Attendance, Credits, Fees Due)
   - Two main sections:
     - **Today’s Classes** (subject, time, room, status)
     - **Announcements** (exam info, hackathon, fee reminder)

This entire app is implemented in a **single HTML file** using:

- React + ReactDOM CDN
- Babel CDN (to support JSX in browser)
- Inline CSS for styling

---

## ✨ Features

- 🔐 **Login form** with basic validation  
- 👤 Different **role labels** (Student / Mentor / Admin) on dashboard  
- 🎨 **Modern UI**:
  - Linear and radial gradients
  - Soft shadows (`box-shadow`)
  - Rounded cards and pills
  - Responsive layout for smaller screens
- 📊 **Stats section**:
  - CGPA card
  - Overall attendance
  - Credit progress
  - Fees due reminder
- 📅 **Schedule section**:
  - Today’s classes with timing, room, faculty, and status badges
- 📢 **Announcements section**:
  - Mid-sem exams
  - Hackathon info
  - Fee payment reminder

---

## 🛠 Tech Stack

- **HTML5**
- **CSS3** (custom styling, gradients, shadows, responsive design)
- **JavaScript (ES6)** + **React 18** (via CDN)
- **ReactDOM 18** (via CDN)
- **Babel Standalone** (to compile JSX directly in browser)

No build tools, no Node.js or bundlers required.  
Perfect for **lab exams** where you just need to show a working React UI quickly.

---

## 📂 File Structure

For this version, the structure is very simple:

```text
.
└── student-portal.html   # Contains React code, CSS, and HTML in one file
