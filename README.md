# Snappy

Snappy is a modern real-time chat application built with the MERN stack. It provides a smooth user experience for authentication, private messaging, avatar selection, and instant communication using Socket.IO.

This project is ideal for showcasing full-stack development skills, real-time features, and a polished React-based interface.

![Login screen](./images/snappy_login.png)

![Chat application interface](./images/snappy.png)

## Features

- User registration and login
- Real-time one-to-one chat
- Online user presence
- Avatar selection for personalized profiles
- Responsive and modern UI
- MongoDB-backed message and user storage

## Tech Stack

- Frontend: React, React Router, Socket.IO Client
- Backend: Node.js, Express.js, Socket.IO
- Database: MongoDB with Mongoose
- Styling: CSS and styled-components

## Project Structure

```text
snappy/
├── frontend/          # React frontend
├── server/            # Express backend and API routes
├── images/            # Screenshots used in this README
└── README.md
```

## Prerequisites

Before running the application, make sure you have:

- Node.js installed
- MongoDB running locally or remotely
- A terminal with npm available

## Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/snappy.git
cd snappy
```

2. Set up the backend environment:

Create a .env file inside the server folder with the following variables:

```env
PORT=5000
MONGO_URL=mongodb://127.0.0.1:27017/snappy
```

3. Install dependencies:

```bash
cd server
npm install

cd ../frontend
npm install
```

4. Start the application:

Open two terminals:

Terminal 1 - Backend:

```bash
cd server
npm start
```

Terminal 2 - Frontend:

```bash
cd frontend
npm start
```

5. Open your browser and visit:

```text
http://localhost:3000
```

## Usage

- Register a new account or log in with an existing one
- Start chatting with other users in real time
- Customize your profile avatar before entering the chat

## Screenshots

- Login experience: [images/snappy_login.png](./images/snappy_login.png)
- Main chat interface: [images/snappy.png](./images/snappy.png)

## Contributing

Contributions are welcome. If you would like to improve the project, feel free to open an issue or submit a pull request.

## Acknowledgements

This project was built as a full-stack chat application example and is intended for learning, development, and portfolio use.