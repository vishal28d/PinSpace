# 📌 PinSpace — A Pinterest-Like Full-Stack App

PinSpace is a **full-stack Pinterest clone** built with **React.js, Node.js, Express, and MongoDB**, featuring media uploads, a custom image editor, emoji comments, infinite scroll, and a clean responsive UI inspired by Pinterest.

This project showcases modern full-stack development with secure authentication, optimized media handling, and real-time UI experiences.

---

## 🚀 Features

### ⭐ Frontend (React.js)

* Fully responsive Pinterest-style masonry grid
* Infinite scrolling for seamless content browsing
* Image upload with:
  ✓ Orientation changes
  ✓ Canvas resizing
  ✓ Text overlays
  ✓ Color adjustments
* Emoji-supported commenting system
* Like, save, follow/unfollow interactions
* User profiles with boards and pins
* Search posts by title, tags, or collections
* React Router v7 dynamic navigation
* Zustand for authentication + editor state
* React Query for caching & real-time UI updates
* Lazy loaded pages for performance

### ⭐ Backend (Node.js + Express)

* RESTful API with Express 5
* MongoDB with Mongoose schemas for users, pins, boards, comments, follows, likes, saves
* JWT-based authentication with cookies (HTTP-only)
* Protected routes with middleware
* Cursor-based pagination for infinite scroll
* Sharp for image processing
* ImageKit integration for optimized media storage
* Regex search for flexible keyword filtering

---

## 🗂️ Project Structure

```
PinSpace/
├── client/        # React.js frontend
└── backend/       # Express + MongoDB API
```

---

## ⚙️ Setup Instructions

### 1️⃣ Clone the repository

```bash
git clone https://github.com/yourusername/pinspace.git
cd pinspace
```

### 2️⃣ Backend Setup

```bash
cd backend
npm install
cp .env.example .env  # Add MongoDB URI, JWT secret, ImageKit keys
npm run dev
```

Backend runs at: **[http://localhost:3000](http://localhost:3000)**

### 3️⃣ Frontend Setup

```bash
cd ../client
npm install
cp .env.example .env  # Add VITE_API_URL
npm run dev
```

Frontend runs at: **[http://localhost:5173](http://localhost:5173)**

---

## 🧩 Core Modules

### 🔐 Authentication

* Register, Login, Logout
* JWT stored in secure HTTP-only cookies
* Persistent auth state via Zustand

### 🖼️ Image Handling

* ImageKit for hosting + transformations
* Sharp on backend for metadata + resizing
* Custom editor for draggable text overlays

### 💬 Interaction Features

* Likes
* Saves
* Comments with emojis
* Follows/Unfollows
* Real-time UI updates using React Query mutations

### 🔍 Search

* Search by title or tags (case-insensitive)
* MongoDB regex-based filtering

---

## 📸 Pages in the App

* **Home** – Masonry feed with infinite scroll
* **Pin Details** – Comments, likes, save, share
* **User Profile** – Pins, boards, followers
* **Create Pin** – Upload + edit image + add metadata
* **Search** – Filter pins by keywords
* **Auth** – Login and Register

---

## 🛠 Tech Stack

### Frontend

* React.js
* React Router v7
* Zustand
* React Query
* TailwindCSS / custom CSS

### Backend

* Node.js
* Express
* MongoDB + Mongoose
* Sharp
* ImageKit SDK

---

## 📈 Future Enhancements

* OAuth login (Google/GitHub)
* Real-time notifications
* Drag & drop board management
* Video pin support
* AI-powered pin recommendations

---

## 🤝 Contributing

Pull requests are welcome! Feel free to fork the repo and improve the project.

---

## 👨‍💻 Author

**Vishal Maurya**
Full-Stack Developer

If you want a portfolio-friendly short version or GitHub badges added, let me know!
