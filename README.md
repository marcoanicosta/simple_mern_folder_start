# MERN Stack Application

A full-stack application built with MongoDB, Express, React, and Node.js.

## Project Structure

```
reader.v1/
├── client/              # React frontend
│   ├── public/
│   └── src/
│       ├── components/  # Reusable UI components
│       ├── pages/       # Page components
│       ├── services/    # API services
│       ├── utils/       # Utility functions
│       ├── App.js
│       ├── index.js
│       └── index.css
├── server/              # Node.js/Express backend
│   ├── config/         # Configuration files
│   ├── controllers/     # Request handlers
│   ├── middleware/      # Custom middleware
│   ├── models/         # Mongoose models
│   ├── routes/         # API routes
│   ├── utils/          # Utility functions
│   └── server.js       # Entry point
└── README.md
```

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- MongoDB (local or cloud instance)
- npm or yarn

### Installation

1. Install server dependencies:
```bash
cd server
npm install
```

2. Install client dependencies:
```bash
cd ../client
npm install
```

3. Configure environment variables:
```bash
cd ../server
cp .env.example .env
# Edit .env with your MongoDB URI and other settings
```

### Running the Application

1. Start the server:
```bash
cd server
npm run dev
```

2. Start the client (in a new terminal):
```bash
cd client
npm start
```

The server will run on `http://localhost:5000`
The client will run on `http://localhost:3000`

## Technologies

- **Frontend**: React, React Router
- **Backend**: Node.js, Express
- **Database**: MongoDB, Mongoose
- **Authentication**: JWT (JSON Web Tokens)

## Development

- Use `npm run dev` in the server folder to run with nodemon for auto-restart
- The client uses Create React App with hot reloading

