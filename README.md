# AI Chatbot (Gemini AI)

A full-stack AI-powered chatbot built using the MERN stack and Google Gemini API. The application provides secure user authentication, persistent conversation history, real-time messaging, and semantic memory retrieval using Pinecone to deliver context-aware AI responses.

---

## Features

- Secure user authentication using JWT and bcrypt
- AI-powered conversations using Google Gemini API
- Persistent chat history with MongoDB
- Semantic vector memory using Pinecone
- Real-time communication using Socket.IO
- Multiple conversation management
- Responsive and modern user interface
- RESTful API architecture following MVC pattern

---

## Tech Stack

### Frontend
- React.js
- Redux Toolkit
- JavaScript
- CSS

### Backend
- Node.js
- Express.js
- MongoDB (Mongoose)
- JWT Authentication
- Socket.IO
- Google Gemini API
- Pinecone Vector Database

### Tools
- Git
- Postman
- VS Code

---

## Project Structure

```
AI-Chatbot
│
├── Backend/
│   ├── src/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middlewares/
│   └── services/
│
├── Frontend/
│   ├── src/
│   ├── components/
│   ├── pages/
│   └── assets/
│
└── README.md
```

---

## Installation

### Clone the repository

```bash
git clone https://github.com/Akamsh07/AI-Chatbot---Gemini-AI.git
```

### Backend

```bash
cd Backend
npm install
```

Create a `.env` file and configure:

```
PORT=
MONGO_URI=
JWT_SECRET=
GEMINI_API_KEY=
PINECONE_API_KEY=
PINECONE_INDEX=
```

Run the backend

```bash
npm start
```

---

### Frontend

```bash
cd Frontend
npm install
npm run dev
```

---

## Technologies Used

- React.js
- Redux Toolkit
- Node.js
- Express.js
- MongoDB
- Google Gemini API
- Pinecone
- Socket.IO
- JWT
- bcrypt

---

## Future Improvements

- Dark Mode
- Export Chats
- Chat Search
- File Upload Support
- AI Response Streaming
- Voice Interaction

---

## Author

**Akash Ghorami**

GitHub: https://github.com/Akamsh07
