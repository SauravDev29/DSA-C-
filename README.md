##FocusTrail is a fully client-side productivity web application built using only HTML, CSS, and vanilla JavaScript — with all data stored locally via localStorage. No backend, no external libraries, no frameworks, no nonsense. Just raw productivity.

📁 Project Structure
index.html – Home/Dashboard

journal/journal.html – Journal Page

about/about.html – About Page

Reusable index.css + page-specific CSS files

All logic handled via modular vanilla JavaScript

localStorage used for persistent state across pages

🏗 Features & Pages
🧠 1. Home Page (Dashboard)
A 3-section productivity dashboard:

Welcome Block: Greeting message, static productivity tabs, and avatar

Pomodoro Timer: 25-minute timer with Focus, Break, Start, Reset buttons

Stats & Motivation: Completed / In-progress / Cancelled tasks + daily quote

✅ All data saved in localStorage
✅ Timer logic purely in JavaScript

📘 2. Journal Page
Reflect, write, and save your daily thoughts:

Write today’s entry (timestamped)

Save journal entry by date

See previous entries in expandable previews

Static journal prompts for creative writing

✅ All entries stored in localStorage
✅ Editable and retrievable by date

🧾 3. About Page
App Mission & Vision

Feature Overview

Benefits of digital focus tools

Optional: Developer credits

🌓 4. Dark/Light Mode (Universal)
Toggle at bottom-right of every page

Uses CSS Variables for easy theme switching

Preference saved in localStorage

Applied globally to all pages

🧩 Common UI & Navigation
Top Navbar: Logo (left), optional icon (right)

Bottom Sticky Nav (mobile-first, all screens):
Home | Diary | About

Current page highlighted in nav

Soft shadows, smooth animations, responsive layout

Icons: Unicode/SVG only – no external CDNs

⚙ Technical Constraints
🔒 No frameworks (React, Bootstrap, jQuery – none)

🔌 No external libraries or CDNs

💾 Only localStorage for all data handling

🔀 Modular CSS & JavaScript, clean and reusable

🗂 Separate HTML files per page

🧠 Inspiration
FocusTrail is designed for deep work lovers, journaling enthusiasts, and digital minimalists who want zero distractions and maximum clarity.

Built with purpose. Served with simplicity.
