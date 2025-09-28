Real-Time Collaborative Code Editor 💻

A real-time collaborative code editor that allows multiple developers to code together simultaneously. Built with React, Node.js, and Socket.io for seamless pair programming and technical interviews.

<img width="1439" height="808" alt="image" src="https://github.com/user-attachments/assets/6a04ce2c-445f-41ec-808f-0f98e1727ea7" />


🌟 Features

Real-Time Collaboration

Live Code Synchronization: See changes from other users as they type
Multi-User Support: Multiple developers can join the same room
User Presence: See who's currently in the room with you
Typing Indicators: Know when others are coding
Multi-Language Support

JavaScript - Perfect for web development
Python - Great for data science and scripting
Java - Enterprise-level programming
C++ - System programming and algorithms
Code Execution

Integrated Compiler: Run code directly in the editor
Real-time Output: See execution results instantly
Input Support: Provide custom input for your programs
Error Handling: Clear error messages and debugging support
Room Management

Shareable Links: Invite others with a single click
Unique Room IDs: Secure, automatically generated room identifiers
Copy to Clipboard: Easy room sharing functionality
🚀 Quick Start

Prerequisites

Node.js (v14 or higher)
npm or yarn
Installation

Clone the repository
bash
git clone https://github.com/jishankhan12/collaborative-code-editor.git
cd collaborative-code-editor
Backend Setup
bash
cd backend
npm install
npm start
Server runs on http://localhost:5003

Frontend Setup (in a new terminal)
bash
cd frontend
npm install
npm start
Application runs on http://localhost:3000

🏗️ Architecture

Frontend (React)

React Hooks: State management with useState and useEffect
Monaco Editor: VS Code-powered code editor
Socket.io Client: Real-time communication
Responsive UI: Clean, modern interface
Backend (Node.js + Express + Socket.io)

Express.js: REST API server
Socket.io: WebSocket connections for real-time updates
In-Memory Storage: Room and user management
Piston API Integration: Code execution service
📸 Screenshots


🛠️ Technology Stack

Frontend

React - UI framework
Monaco Editor - Code editing component
Socket.io-client - Real-time communication
UUID - Unique identifier generation
Lodash - Utility functions
Backend

Node.js - Runtime environment
Express.js - Web framework
Socket.io - Real-time engine
Axios - HTTP client for API calls
💡 Use Cases

🎯 Technical Interviews

Conduct live coding interviews
Real-time problem solving
Multiple interviewers can observe
👥 Pair Programming

Remote team collaboration
Code review sessions
Mentoring and training
🏫 Educational Purposes

Classroom coding exercises
Student group projects
Live coding demonstrations
🔧 API Reference

Socket Events

Client to Server

join - Join a room
codeChange - Send code updates
languageChange - Change programming language
compileCode - Execute code
typing - Send typing indicators
Server to Client

userJoined - User joined notification
codeUpdate - Code synchronization
languageUpdate - Language change broadcast
codeResponse - Execution results
userTyping - Typing indicators
🚀 Deployment

Local Development

bash
# Backend (Terminal 1)
cd backend && npm run dev

# Frontend (Terminal 2) 
cd frontend && npm start
Production Deployment

bash
# Build frontend
cd frontend && npm run build

# Start production server
cd backend && npm start
🤝 Contributing



Built with ❤️ using React, Node.js, and Socket.io

</div>
🔗 Quick Links

Live Demo ((https://realtimecodecollaabrative.netlify.app))

Happy Coding! 🎉
