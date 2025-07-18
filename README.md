# Facebook Clone

A full-stack Facebook clone built with the MERN stack (MongoDB, Express.js, React.js, Node.js).
Create Account 
![F15BC3A5-182B-453F-8176-98AAA210FBED_1_105_c](https://github.com/user-attachments/assets/2796ab62-6ee6-45cd-ae09-a96a5a3fded8)
Profile page

![FE5FA96C-BBD4-49A0-8E83-DA924C2B6833_1_105_c](https://github.com/user-attachments/assets/4d3c4cc5-4419-4df7-b425-cce7513b3ab3)

## Features

- User Authentication (Signup, Login, Logout)
- News Feed
- Create/Edit/Delete Posts
- Like and Comment System
- Friend System
- Profile Pages
- Real-time Notifications

## Tech Stack

- **Frontend**: React.js, Redux Toolkit, Material-UI
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Real-time**: Socket.io
- **Authentication**: JWT
- **File Storage**: Cloudinary

## Project Structure

```
facebook-clone/
├── client/                 # React frontend
├── server/                 # Node.js backend
├── .gitignore
└── README.md
```

## Setup Instructions

### Prerequisites

- Node.js (v14 or higher)
- MongoDB
- npm or yarn

### Installation

1. Clone the repository
```bash
git clone <repository-url>
cd facebook-clone
```

2. Install backend dependencies
```bash
cd server
npm install
```

3. Install frontend dependencies
```bash
cd ../client
npm install
```

4. Create a .env file in the server directory with the following variables:
```
MONGODB_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret
```

5. Start the development servers

Backend:
```bash
cd server
npm run dev
```

Frontend:
```bash
cd client
npm start
```

The application will be available at:
- Frontend: http://localhost:3000
- Backend: http://localhost:5000

## Contributing

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Create a new Pull Request 
