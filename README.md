# 🎥 YouTube Clone (React + Vite + YouTube Data API v3)

A responsive **YouTube Clone** built with **React (via Vite)**.  
Features include home feed, video playback, recommendations, sidebar categories, and more. Data is fetched live from the **YouTube Data API v3**.

## ✨ Features

- 🔍 Search videos  
- 🏠 Browse recommended/trending feed  
- 📺 Watch video with player & details  
- 📑 Sidebar navigation with categories  
- 📱 Responsive layout for all devices  
- ⚠️ Error handling for failed API calls  
- 🎨 Clean UI with modular components  

---

## 🛠️ Tech Stack

- **Frontend:** React 18, Vite  
- **Routing:** React Router DOM  
- **API:** YouTube Data API v3  
- **HTTP Client:** Fetch   
- **Styling:** CSS Modules (separate `.css` files per component)  

---

## 📂 Project Structure

```bash
src/
├── assets/                 # Images, icons, static assets
│
├── Components/             # Reusable UI building blocks
│   ├── Feed/
│   │   ├── Feed.jsx
│   │   └── Feed.css
│   ├── Navbar/
│   │   ├── Navbar.jsx
│   │   └── Navbar.css
│   ├── PlayVideo/
│   │   ├── PlayVideo.jsx
│   │   └── PlayVideo.css
│   ├── Recommended/
│   │   ├── Recommended.jsx
│   │   └── Recommended.css
│   └── Sidebar/
│       ├── Sidebar.jsx
│       └── Sidebar.css
│
├── Pages/                  # Page-level components (routes)
│   ├── Home/
│   │   ├── Home.jsx
│   │   └── Home.css
│   └── Video/
│       ├── Video.jsx
│       └── Video.css
│
├── App.jsx                 # Root component
├── data.js                 # Static data/constants (categories, dummy data)
├── index.css               # Global styles
├── main.jsx                # React entry (Vite)

