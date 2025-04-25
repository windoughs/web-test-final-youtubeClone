

# YouTube Clone - MERN Stack

A full-stack YouTube clone built with MongoDB, Express, React, and Node.js (MERN stack).

## Features

- User Authentication (Register/Login)
- Video Upload and Playback
- Like/Dislike Videos
- Comment System
- Search Functionality
- Category Filtering
- Responsive Design

## Tech Stack

- *Frontend:*
  - React
  - React Router
  - Tailwind CSS
  - Lucide Icons

- *Backend:*
  - Node.js
  - Express.js
  - MongoDB
  - JWT Authentication
  - Multer (File Upload)

## Prerequisites

- Node.js (v14 or higher)
- MongoDB (local or Atlas)
- npm or yarn

## Installation

1. Clone the repository:
bash
git clone https://github.com/yourusername/youtube-clone.git
cd youtube-clone


2. Install server dependencies:
bash
cd server
npm install


3. Install client dependencies:
bash
cd ../client
npm install


4. Create a .env file in the server directory:
env
PORT=5000
MONGODB_URI=mongodb://localhost:27017/youtube-clone
JWT_SECRET=your_jwt_secret_key_here
JWT_EXPIRE=30d


5. Start the development servers:

In the server directory:
bash
npm run dev


In the client directory:
bash
npm run dev


The application will be available at:
- Frontend: http://localhost:5173
- Backend: http://localhost:5000

## Project Structure


youtube-clone/
├── client/                 # React frontend
│   ├── public/
│   └── src/
│       ├── components/     # React components
│       ├── App.jsx         # Main App component
│       └── main.jsx        # Entry point
├── server/                 # Express backend
│   ├── models/            # MongoDB models
│   ├── routes/            # API routes
│   ├── middleware/        # Custom middleware
│   └── index.js           # Server entry point
└── README.md


## API Endpoints

### Authentication
- POST /api/auth/register - Register a new user
- POST /api/auth/login - Login user

### Videos
- GET /api/videos - Get all videos
- GET /api/videos/:id - Get video by ID
- POST /api/videos - Upload a new video
- POST /api/videos/:id/like - Like a video
- POST /api/videos/:id/dislike - Dislike a video

### Comments
- POST /api/videos/:id/comments - Add a comment
- GET /api/videos/:id/comments - Get video comments

## Contributing

1. Fork the repository
2. Create your feature branch (git checkout -b feature/AmazingFeature)
3. Commit your changes (git commit -m 'Add some AmazingFeature')
4. Push to the branch (git push origin feature/AmazingFeature)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- YouTube for inspiration
- MERN stack community
1. Navigate to the server directory:
   bash
   cd server
   

2. Install dependencies:
   bash
   npm install
   

3. Create a .env file with the following variables:
   
   PORT=5000
   MONGODB_URI=your_mongodb_uri
   JWT_SECRET=your_jwt_secret
   

4. Start the server:
   bash
   npm start
   

### Frontend Setup

1. Navigate to the client directory:
   bash
   cd client
   

2. Install dependencies:
   bash
   npm install
   

3. Start the development server:
   bash
   npm start
   

## API Endpoints

- POST /api/auth/register - User registration
- POST /api/auth/login - User login
- GET /api/videos - Get all videos
- POST /api/videos - Upload new video
- GET /api/videos/:id - Get video details
- POST /api/videos/:id/comments - Add comment
- PUT /api/videos/:id/like - Like video
- PUT /api/videos/:id/dislike - Dislike video

## Contributing

Feel free to submit issues and enhancement requests.