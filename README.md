# Blog App

A full-stack blog application built with the MERN (MongoDB, Express, React, Node.js) stack.

## Features

- View a list of blog posts
- Read individual blog posts
- Create new blog posts
- Edit existing blog posts
- Delete blog posts
- Responsive design for mobile and desktop

## Technologies Used

- Frontend: React, React Router, Axios
- Backend: Node.js, Express.js, MongoDB with Mongoose
- Additional: Cors for cross-origin resource sharing

## Getting Started

### Prerequisites

- Node.js (v14 or later)
- MongoDB

### Installation

1. Clone the repository:
   ```bash:
   git clone https://github.com/M-Haris7/Blog-app.git
    cd Blog-app
   ```
2. Install server dependencies:
   ```bash:
   cd server
   npm install
   ```
3. Install client dependencies:
   ```bash:
   cd ../client
   npm install
   ```
4. Create a `.env` file in the server directory and add your MongoDB connection string:
   ```bash:
   MONGODB_URI=your_mongodb_connection_string
   ```
### Running the Application

1. Start the server:
```bash:
cd server
npm start
```
2. In a new terminal, start the client:
```bash:
cd client
npm start
```
3. Open your browser and navigate to `http://localhost:3000`

## API Endpoints

- GET `/posts` - Retrieve all posts
- GET `/posts/:id` - Retrieve a specific post
- POST `/posts` - Create a new post
- PUT `/posts/:id` - Update a specific post
- DELETE `/posts/:id` - Delete a specific post

## Deployment

This application is deployed on Vercel. The frontend and backend are deployed separately:

- Frontend: [Your frontend URL]
- Backend API: [Your backend URL]


