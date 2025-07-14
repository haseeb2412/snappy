📱 Snappy – Real‑Time Chat App
A full‑stack real‑time chat application built using the MERN stack (MongoDB, Express, React, Node.js) and Socket.io. Inspired by the original YouTube tutorial by koolkishan 
GitHub
+7
GitHub
+7
YouTube
+7
.

🧭 Project Overview
Real-time messaging between users

User authentication with secure login

MongoDB database for storing users & chat history

Responsive UI built with React

WebSocket communication via Socket.io

Styled components in the frontend for UI consistency 
GitHub
+3
Built At Lightspeed
+3
Reddit
+3

📦 Tech Stack & Key Libraries
Layer	Technology / Library	Purpose
Backend	Node.js + Express	Server creation and routing
MongoDB + Mongoose	Persistent data storage
Socket.io	Real-time, bidirectional communication
Frontend	React	UI development
React Router	Client-side routing
Styled Components	Styling React components 
YouTube
+5
Medium
+5
Reddit
+5
General	dotenv	Environment variables
cors	Cross-Origin Resource Sharing
Dev & Deployment	Docker + Docker Compose	Optional containerized setup

🚀 Setup & Installation
Prerequisites
Node.js, npm or yarn

MongoDB (running locally, or via Docker)

(Optional) Docker & Docker Compose for containerized deployment 
Reddit
+7
GitHub
+7
GitHub
+7

🛠️ Local Development (Manual)

git clone https://github.com/koolkishan/chat-app-react-nodejs.git
cd chat-app-react-nodejs

# Setup environment variables
cd public && mv .env.example .env && cd ../server && mv .env.example .env

# Install dependencies
cd server && yarn
cd ../public && yarn

# Run the servers
# Backend
cd ../server && yarn start
# Frontend
cd ../public && yarn start
Backend defaults to port 5000

Frontend runs on port 3000

Open your browser at http://localhost:3000 
Reddit
+6
GitHub
+6
Built At Lightspeed
+6


📁 Project Structure


/public      # React frontend
  ├─ src
  └─ .env.example

/server      # Node.js API + Socket.io server
  ├─ models
  ├─ routes
  ├─ controllers
  ├─ .env.example
  └─ server.js (main entry)
✅ Running Tests
The project doesn’t include tests out-of-the-box, but you can easily integrate:

Jest for backend testing

React Testing Library for frontend components