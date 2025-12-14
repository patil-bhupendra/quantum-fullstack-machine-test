# Full Stack Machine Test – Quantum IT Innovation

This project is a full stack authentication system built as part of the machine test for Quantum IT Innovation.

## Features
- User registration and login
- JWT-based authentication
- Protected dashboard route
- User data stored in MongoDB
- Static table displayed after successful login
- Logout functionality

## Tech Stack
- Frontend: React.js, Vite, Tailwind CSS
- Backend: Node.js, Express.js
- Database: MongoDB Atlas
- Authentication: JSON Web Token (JWT)

## Project Structure
client/ - React frontend
server/ - Node.js backend


## Setup Instructions

### Backend
```bash
cd server
npm install
npm run dev

```
Create a .env file in the server folder with:

```
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret

```

```
### Frontend
cd client
npm install
npm run dev

The frontend will run on:
http://localhost:5173

```
