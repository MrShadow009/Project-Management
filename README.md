# 🚀 ProjectPulse — Project Management System (SaaS UI)

A modern, premium **Project Management System** inspired by Trello/Jira/Asana with a glassmorphism design, interactive dashboard, Kanban board, tasks & projects management, local persistence, analytics (Chart.js), theming (Light/Dark), and responsive UI — **no backend, no database, no login**.

## ✨ Live Deployment

**Vercel Link:** https://project-management-dusky-seven.vercel.app/

## 🧠 Features (Highlights)

- **Dashboard (SaaS-style)**
  - Total projects & tasks counters
  - Completed / pending tracking
  - Progress indicator
  - Recent activities, upcoming deadlines, notifications

- **Projects Module**
  - Create / edit / delete / archive
  - Search, filter & sort

- **Tasks Module**
  - Add / edit / delete / archive
  - Search / filter / sort
  - Duplicate task (UI demo)

- **Kanban Board**
  - Drag & drop between columns
  - Real-time UI updates
  - Status & progress consistency

- **Team Members**
  - Manage members via LocalStorage
  - Profile-style cards & status badges

- **Calendar View**
  - Month grid
  - Deadline highlighting
  - Upcoming deadlines & overdue detection

- **Reports + Analytics**
  - Summary report cards
  - Chart.js visualizations
  - Export options (CSV/JSON demo)

- **Settings + Dark Mode**
  - Persist theme preferences
  - Notification controls

- **Local Storage Persistence**
  - Projects, Tasks, Members, Settings, Notifications, Activities survive refresh

## 🛠️ Tech Stack

- **HTML5**
- **CSS3** (Glassmorphism + premium UI)
- **JavaScript (LocalStorage)**
- **Bootstrap 5**
- **Font Awesome Icons**
- **Chart.js**

## 📦 Project Structure

- `index.html` — Dashboard
- `dashboard.html` — Dashboard (alt entry)
- `projects.html` — Projects table
- `tasks.html` — Tasks table
- `kanban.html` — Kanban board
- `team.html` — Team members
- `calendar.html` — Calendar view
- `reports.html` — Analytics & reports
- `settings.html` — Theme & notifications
- `about.html` — Help / About
- `style.css` — Premium responsive styling
- `script.js` — App logic, LocalStorage schema, rendering, drag-drop, charts
- `assets/` — (optional) icons/images

## 🚀 Deploy on Vercel (Static)

1. Push the project to GitHub.
2. Import into Vercel.
3. Ensure it is deployed as a **Static Site**.
4. Use the provided `vercel.json` rewrite to route all requests to `/`.

## 📌 Notes

- This project is designed for **final-year mini project / resume showcase / GitHub demo**.
- It intentionally avoids:
  - Backend APIs
  - Login/authentication
  - Database connectivity

## 🖼️ Screens / Demo

Open the deployed link and try:
- Add/edit tasks & move cards on the Kanban board
- Toggle Dark Mode
- Check Reports charts

---

⭐ Built with focus on clean UX, premium aesthetics, and performance-friendly LocalStorage rendering.

