# LMS Frontend

A frontend prototype for a Learning Management System (LMS), built with React and Vite. It includes course browsing, a student dashboard, authentication screens, and certificate/settings pages, currently powered by static mock data.

## Tech Stack

Frontend: HTML, CSS, JavaScript / React /vite

## Features

- 🏠 Course catalog and course details pages
- 🔐 Authentication screens (Login, Register)
- 📊 Student dashboard with My Courses, Certificates, and Settings
- 🧩 Reusable components (Navbar, Footer, Course Card, Dashboard Sidebar)
- 🎨 Global styling via CSS

> **Note:** This is currently a frontend-only build. Data is sourced from a local mock file (`src/data/coursesData.js`), and the `services/`, `store/`, and `hooks/` directories are scaffolded for future API integration and state management but not yet implemented.

## Project Structure

```
LMS-Frontend/
├── public/                  # Static assets (icons, favicon)
├── src/
│   ├── assets/               # Images
│   ├── components/           # Reusable UI components (Navbar, Footer, CourseCard, etc.)
│   ├── data/                 # Mock data (coursesData.js)
│   ├── hooks/                # Custom React hooks (scaffold)
│   ├── layouts/              # Page layout wrappers (MainLayout, AuthLayout)
│   ├── pages/
│   │   ├── Admin/             # Admin dashboard
│   │   ├── Auth/               # Login, Register, Forgot Password
│   │   ├── Courses/             # Course list, course details, courses page
│   │   └── Dashboard/            # Student dashboard, My Courses, Certificates, Settings
│   ├── routes/                # App route definitions
│   ├── services/              # API service layer (scaffold)
│   ├── store/                 # State management (scaffold)
│   ├── styles/                # Global CSS
│   ├── App.jsx
│   └── main.jsx
├── index.html
├── package.json
└── vite.config.js
```

## Purpose of the Project

This project was built as part of academic learning and internship experience to understand real-world dashboard development, UI structuring, and basic frontend concepts
