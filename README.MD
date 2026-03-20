<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=32&pause=1000&color=6C63FF&center=true&vCenter=true&width=600&lines=💬+Chatify;Real-Time+Chat+App;Built+with+Socket.io" alt="Chatify Typing SVG" />

<br/>

<p align="center">
  <b>A full-stack real-time chat application — sign up, log in, and start chatting instantly.</b><br/>
  <i>Messages fly in real time, no page refresh needed.</i>
</p>

<br/>

[![Node.js](https://img.shields.io/badge/Node.js-20+-339933?logo=node.js&logoColor=white)](https://nodejs.org)
[![React](https://img.shields.io/badge/React-19-61DAFB?logo=react&logoColor=black)](https://react.dev)
[![Socket.io](https://img.shields.io/badge/Socket.io-4.x-010101?logo=socket.io)](https://socket.io)
[![MongoDB](https://img.shields.io/badge/MongoDB-Atlas-47A248?logo=mongodb&logoColor=white)](https://mongodb.com)
[![TailwindCSS](https://img.shields.io/badge/Tailwind-CSS-06B6D4?logo=tailwindcss&logoColor=white)](https://tailwindcss.com)
[![License: ISC](https://img.shields.io/badge/License-ISC-blue.svg)](https://opensource.org/licenses/ISC)

</div>

---

## ⚡ What is Chatify?

> **Chatify** is a production-ready, real-time chat application. Create an account, see who's online, and exchange messages instantly — no refreshing, just pure WebSocket magic.

---

## 🎯 Features at a Glance

| Feature | Description |
|---|---|
| 🔐 **JWT Auth** | Secure login & signup — no 3rd-party auth needed |
| ⚡ **Real-Time Chat** | Instant messaging via Socket.io WebSockets |
| 🟢 **Online Presence** | See who's online/offline in real time |
| 🔔 **Sound Notifications** | Audio cues for new messages (toggleable) |
| 📨 **Welcome Emails** | Auto email on signup via Resend |
| 🖼️ **Image Uploads** | Share images powered by Cloudinary |
| 🚦 **Rate Limiting** | API protection via Arcjet |
| 🎨 **Beautiful UI** | React + Tailwind CSS + DaisyUI |

---

## 🛠️ Tech Stack

### Frontend
- ⚛️ **React 19** — Component-based UI
- 🎨 **Tailwind CSS + DaisyUI** — Styling
- 🔌 **Socket.io-client** — Real-time connection
- 🧠 **Zustand** — Lightweight state management
- 🔀 **React Router v7** — Client-side routing

### Backend
- 🟢 **Node.js + Express** — REST API server
- 🔌 **Socket.io** — WebSocket server
- 🗄️ **MongoDB + Mongoose** — Database
- 🔑 **JWT + bcryptjs** — Auth & password hashing
- 📧 **Resend** — Transactional emails
- ☁️ **Cloudinary** — Image storage
- 🛡️ **Arcjet** — Rate limiting & bot protection

---

## 🚀 Quick Start

### Prerequisites
- Node.js ≥ 20
- MongoDB Atlas account (free tier works)

### 1. Clone the repo
```bash
git clone https://github.com/aaadityasngh/chatify-real-time-chating-with-socket.io.git
cd chatify-real-time-chating-with-socket.io
```

### 2. Set up environment variables

Create `/backend/.env` with the following:

```env
PORT=3000
MONGO_URI=your_mongo_uri_here
NODE_ENV=development

JWT_SECRET=your_jwt_secret

RESEND_API_KEY=your_resend_api_key
EMAIL_FROM=your_email_from_address
EMAIL_FROM_NAME=your_email_from_name

CLIENT_URL=http://localhost:5173

CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret

ARCJET_KEY=your_arcjet_key
ARCJET_ENV=development
```

### 3. Install & run

**Backend:**
```bash
cd backend
npm install
npm run dev        # runs on http://localhost:3000
```

**Frontend** (new terminal):
```bash
cd frontend
npm install
npm run dev        # runs on http://localhost:5173
```

Open **http://localhost:5173** — you're live! 🎉

---

## 📁 Project Structure

```
chatify/
├── backend/
│   └── src/
│       ├── controllers/   # Route handlers
│       ├── models/        # Mongoose schemas
│       ├── routes/        # Express routes
│       ├── middleware/    # Auth & error middleware
│       ├── lib/           # DB, Socket.io, Cloudinary setup
│       ├── emails/        # Email templates
│       └── server.js      # App entry point
│
└── frontend/
    └── src/
        ├── pages/         # LoginPage, SignUpPage, ChatPage
        ├── components/    # Reusable UI components
        ├── store/         # Zustand state stores
        ├── hooks/         # Custom React hooks
        └── lib/           # Axios instance, socket client
```

---

## ☁️ Deployment

The app is **free-tier friendly** and can be deployed on platforms like **Sevalla**, **Render**, or **Railway**.

```bash
# Build everything from root
npm run build

# Start the production server
npm start
```

> 💡 The backend serves the frontend's build files in production — just one server to deploy!

---

## 🤝 Contributing

1. Fork the repo
2. Create a feature branch: `git checkout -b feature/your-feature`
3. Commit changes: `git commit -m "feat: add your feature"`
4. Push & open a Pull Request

---

<div align="center">

Made with ❤️ by [Aaditya Singh](https://github.com/aaadityasngh)

⭐ **Star this repo if you found it helpful!**

</div>
