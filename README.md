# MERN Chatting App (Messenger)

A real-time chat application built using the **MERN (MongoDB, Express, React, Node.js) stack**, where users can create accounts, send messages, and change the background theme.

## Features
- ✅ **User Authentication** – Signup/Login with JWT authentication
- ✅ **Real-Time Messaging** – Send and receive messages instantly
- ✅ **Chat Rooms** – One-to-one and group chats
- ✅ **Profile Management** – Users can update their profile
- ✅ **Theme Customization** – Change the chat background theme
- ✅ **Online Status** – See which users are online
- ✅ **Secure Backend** – Uses bcrypt for password hashing

---

## Tech Stack
### Frontend
- React.js
- Tailwind CSS
- React Router
- Redux (optional for state management)
- Socket.io-client (for real-time communication)

### Backend
- Node.js
- Express.js
- MongoDB (Mongoose for database management)
- JWT (for authentication)
- bcrypt.js (for password encryption)
- Socket.io (for real-time communication)

---

## Installation & Setup
### 1. Clone the Repository
```sh
git clone https://github.com/yourusername/mern-chat-app.git
cd mern-chat-app
```

### 2. Backend Setup
```sh
cd backend
npm install
```
#### Environment Variables (`.env` file)
Create a `.env` file in the `backend` directory and add:
```env
PORT=8000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```
#### Run the Server
```sh
npm start
```

---

### 3. Frontend Setup
```sh
cd frontend
npm install
```
#### Run the React App
```sh
npm run dev
```

---

## API Endpoints
### User Authentication
| Method | Endpoint               | Description             |
|--------|------------------------|-------------------------|
| POST   | `/api/v1/user/register` | Register a new user     |
| POST   | `/api/v1/user/login`    | Login user             |
| GET    | `/api/v1/user/logout`   | Logout user            |

### Chat Routes
| Method | Endpoint              | Description                  |
|--------|-----------------------|------------------------------|
| GET    | `/api/v1/chat`        | Get all user chats           |
| POST   | `/api/v1/chat`        | Create a new chat            |
| GET    | `/api/v1/chat/:id`    | Get messages of a chat       |
| POST   | `/api/v1/message`     | Send a message               |

---

## Screenshots
🚀 Coming soon..



## License
This project is **MIT Licensed**.
