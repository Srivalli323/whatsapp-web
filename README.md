# 💬 WhatsApp Web Clone (MERN + WebRTC)

A full-stack real-time chat application inspired by WhatsApp Web, featuring messaging, group chats, file sharing, and peer-to-peer audio/video calling.

---

## 🚀 Features

### 💬 Messaging
- One-to-one real-time chat
- Group chat support
- Instant message delivery using WebSockets

### 🟢 Presence & Activity
- Online/offline status
- Typing indicators

### 📞 Calling
- Audio calling using WebRTC
- Video calling using WebRTC
- Peer-to-peer connection for low latency communication

### 📁 File Sharing
- Upload and send files/media
- Cloud storage integration (Cloudinary)

### 🔐 Authentication & Security
- JWT-based authentication
- Protected routes and secure APIs

### 🎨 UI/UX
- Responsive WhatsApp-like interface
- Dark mode support
- Built with Tailwind CSS

---

## 🛠️ Tech Stack

### Frontend
- React.js
- Redux Toolkit
- Tailwind CSS

### Backend
- Node.js
- Express.js
- MongoDB
- JWT (JSON Web Tokens)

### Real-Time Communication
- Socket.io (WebSockets)
- WebRTC (Audio/Video calls)

---

## 📂 Project Structure

```
whats_app_project/
│
├── backend/
│   ├── src/
│   │   ├── configs/
│   │   ├── controllers/
│   │   ├── middlewares/
│   │   ├── models/
│   │   ├── routes/
│   │   ├── services/
│   │   ├── utils/
│   │   │
│   │   ├── app.js
│   │   ├── index.js
│   │   └── SocketServer.js
│   │
│   ├── .gitignore
│   ├── package.json
│
├── frontend/
│   ├── public/
│   ├── src/
│   │
│   ├── .gitignore
│   ├── package.json
│   ├── package-lock.json   # or yarn.lock (only one)
│   ├── tailwind.config.js
│
└── README.md
```
---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository

```bash
git clone https://github.com/your-username/whatsapp_project.git
cd whatsapp_project
```

### 2️⃣ Setup Backend

```bash
cd server
npm install
```

Run backend:

```bash
npm run dev
```

---

### 3️⃣ Setup Frontend

```bash
cd client
npm install
npm start
```

---

## 📸 Screenshots

Register Page:

<img width="1897" height="880" alt="image" src="https://github.com/user-attachments/assets/3e513368-8021-4912-a172-2663f83470ee" />



Login Page: 

<img width="1920" height="881" alt="image" src="https://github.com/user-attachments/assets/6a7548c6-2d1b-4862-ad74-a22f8ae36e77" />


Create new chat:

<img width="1920" height="882" alt="image" src="https://github.com/user-attachments/assets/54c614bc-25ef-44aa-91c4-7e9cc863fdbf" />


One-to-one chat:

<img width="1920" height="835" alt="image" src="https://github.com/user-attachments/assets/daeb93c0-c1c1-4c43-a68b-832592c27dcf" />


Group chat:

<img width="1883" height="843" alt="image" src="https://github.com/user-attachments/assets/c96c7af4-d9e7-4af1-a42a-73fb7c79984b" />


Video call:

<img width="1885" height="843" alt="image" src="https://github.com/user-attachments/assets/763d3747-81c5-49d0-a1b5-07726ac632b8" />


Audio call:

<img width="1871" height="844" alt="image" src="https://github.com/user-attachments/assets/ba40be68-cdba-4f91-bae6-bec371506c12" />


---

## 🧠 Key Concepts

- Real-time communication using Socket.io
- Peer-to-peer media streaming using WebRTC
- State management using Redux Toolkit
- RESTful API design
- Secure authentication using JWT
- File handling and cloud uploads

---



## 📄 License

This project is licensed under the MIT License.

---

## ⭐ Support

If you like this project, give it a ⭐ on GitHub!

---

## 🧑‍💻 Author

Muthyala Srivalli,
Priyanka Prajapati

