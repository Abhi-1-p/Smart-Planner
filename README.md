📅 Planorra — Smart Daily Planner

Planorra is a modern, real-time, glass-UI daily planner built with Firebase Authentication, Cloud Firestore, and vanilla HTML/CSS/JS.
It is fully compatible with GitHub Pages, Vercel, and all static hosting platforms.

⭐ Features
🔐 Secure Authentication

Email/Password login using Firebase Authentication

Safe and persistent user sessions

User-scoped data access (each user sees only their own planner)

📓 Daily Planning Tools

Priority list

Task manager

Hourly schedule

Journal with autosave

Hydration tracker

Mood / Productivity / Health ratings

📊 Smart Insights

Mood trend

Productivity trend

Hydration consistency

Task completion percentage

Rendered with Chart.js

🔎 Powerful Search

Keyword-indexed search using Firestore array-contains

Fast retrieval of entries containing specific terms

🎨 Personalization

Six customizable color themes

Dark mode toggle

Adaptive glassmorphism UI

🔄 Real-Time Sync

Uses Firestore live listeners (onSnapshot)

Updates instantly across multiple devices

🧩 Tech Stack
Component	Technology
Frontend	HTML, TailwindCSS, JavaScript
Authentication	Firebase Auth
Database	Cloud Firestore (NoSQL)
Charts	Chart.js
Hosting	GitHub Pages / Vercel
📁 Project Structure
project/
│
├── index.html        # Main app (UI + logic)
├── README.md         # Project documentation
└── assets/           # Optional images, icons, logos
