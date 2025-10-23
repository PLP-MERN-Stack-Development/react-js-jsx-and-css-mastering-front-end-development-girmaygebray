🎨 Week 3: React.js, JSX, and Tailwind CSS – Mastering Front-End Development
🚀 Overview

This project is part of the Front-End Development Module (Week 3) and focuses on building a responsive React application using JSX and Tailwind CSS.
The project demonstrates component architecture, state management with React hooks, context for theme handling, and API integration using React best practices.

🧩 Features
🏗️ Component Architecture

Reusable UI components (Button, Card, Navbar, Footer)

Layout with consistent header and footer

Props-driven customization

⚙️ State Management & Hooks

Custom TaskManager app with:

Add, complete, delete, and filter tasks

React hooks:

useState – for state handling

useEffect – for data persistence and side effects

useContext – for global theme control

useLocalStorage – custom hook for persistent tasks

🌐 API Integration

Fetches posts from JSONPlaceholder

Search, pagination, and error handling included

Uses Axios for HTTP requests

🎨 Styling with Tailwind CSS

Responsive design for mobile, tablet, and desktop

Theme switcher (light/dark mode)

Tailwind utility classes for spacing, layout, and typography

Smooth transitions and hover effects

🗂️ Project Structure
src/
├─ components/
│  ├─ ui/
│  │  ├─ Button.jsx
│  │  ├─ Card.jsx
│  │  ├─ Navbar.jsx
│  │  └─ Footer.jsx
│  └─ Footer.jsx
├─ hooks/
│  └─ useLocalStorage.js
├─ pages/
│  ├─ Home.jsx
│  ├─ TasksPage.jsx
│  └─ ApiDataPage.jsx
├─ services/
│  └─ api.js
├─ App.jsx
├─ main.jsx
└─ index.css

🧪 Expected Outcome

A fully functional React app with:

Component-driven structure

Hook-based state management

API integration with error/loading states

Responsive and themed UI

🛠️ Setup Instructions
Prerequisites

Node.js v18+

npm or yarn

Steps

Clone your repository

git clone <your-repo-url>
cd <project-folder>


Install dependencies

npm install


Run the development server

npm run dev


Build for production

npm run build


Preview production build

npm run preview

🧠 How It Works
Task Manager

Add new tasks via input box

Toggle completed status with checkbox

Delete tasks individually

Filter tasks by “All”, “Active”, or “Completed”

Data persists across sessions using localStorage

API Page

Fetches posts from JSONPlaceholder

Includes pagination, search, and loading states

Displays results in a responsive grid

Theme Management

Light/dark mode toggle stored in localStorage

Uses Tailwind’s darkMode: "class" configuration

✅ Submission Checklist

✔️ All components implemented
✔️ Hooks (useState, useEffect, useContext, useLocalStorage) used
✔️ API data fetched and rendered
✔️ Tailwind responsive design applied
✔️ Theme switcher functional
✔️ README.md updated with screenshots and demo link
✔️ Code committed and pushed to GitHub

👨‍💻 Author

Girmay Gebray Aduomer
📧 ggebray@gmail.com

🌍 Addis Ababa, Ethiopia
