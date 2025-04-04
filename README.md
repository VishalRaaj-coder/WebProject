# Notes Application

A feature-rich notes application built with React.js and MongoDB.

## Features

- ✍️ Create & Edit Notes with rich text formatting
- 💾 Automatic saving to local storage
- 🌓 Dark/Light mode toggle
- 📤 Export notes as .txt or .pdf
- 🏷️ Tag-based organization system

## Tech Stack

- Frontend: React.js
- Backend: Node.js with Express
- Database: MongoDB
- Styling: Tailwind CSS

## Setup Instructions

1. Clone the repository
2. Install dependencies:
   ```bash
   # Install backend dependencies
   cd backend
   npm install

   # Install frontend dependencies
   cd ../frontend
   npm install
   ```

3. Create a `.env` file in the backend directory with your MongoDB connection string:
   ```
   MONGODB_URI=your_mongodb_connection_string
   PORT=5000
   ```

4. Start the development servers:
   ```bash
   # Start backend server
   cd backend
   npm run dev

   # Start frontend server
   cd frontend
   npm start
   ```

5. Open http://localhost:3000 in your browser

## Project Structure

```
notes-app/
├── frontend/          # React frontend application
├── backend/           # Node.js backend server
└── README.md         # Project documentation
``` 