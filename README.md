# MeetSphere

A modern video conferencing application built with React.js frontend and Node.js backend, featuring real-time video communication, user authentication, and meeting history.

## 🚀 Features

- **Real-time Video Conferencing**: High-quality video and audio communication
- **User Authentication**: Secure login and registration system
- **Meeting History**: Track and manage your past meetings
- **Responsive Design**: Works seamlessly on desktop and mobile devices
- **Modern UI/UX**: Beautiful and intuitive user interface
- **Socket.io Integration**: Real-time communication capabilities

## 🛠️ Tech Stack

### Frontend
- React.js
- Socket.io-client
- CSS Modules
- Context API for state management

### Backend
- Node.js
- Express.js
- Socket.io
- MongoDB (for user data and meeting history)

## 📦 Installation

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn
- MongoDB (for backend)

### Backend Setup

1. Navigate to the backend directory:
```bash
cd backend
```

2. Install dependencies:
```bash
npm install
```

3. Create a `.env` file in the backend directory with your configuration:
```env
PORT=5000
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
```

4. Start the backend server:
```bash
npm start
```

### Frontend Setup

1. Navigate to the frontend directory:
```bash
cd frontend
```

2. Install dependencies:
```bash
npm install
```

3. Create a `.env` file in the frontend directory:
```env
REACT_APP_BACKEND_URL=http://localhost:5000
```

4. Start the development server:
```bash
npm start
```

## 🎯 Usage

1. **Registration/Login**: Create an account or sign in to access the application
2. **Create Meeting**: Start a new video conference
3. **Join Meeting**: Enter a meeting ID to join an existing session
4. **Video Controls**: Use the video controls to mute/unmute, turn camera on/off
5. **Meeting History**: View your past meetings in the history section

## 📁 Project Structure

```
MeetSphere/
├── backend/
│   ├── src/
│   │   ├── controllers/
│   │   ├── models/
│   │   ├── routes/
│   │   └── app.js
│   ├── package.json
│   └── .env
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── contexts/
│   │   ├── utils/
│   │   └── styles/
│   ├── public/
│   ├── package.json
│   └── .env
└── README.md
```

## 🔧 Configuration

### Environment Variables

**Backend (.env)**
- `PORT`: Server port (default: 5000)
- `MONGODB_URI`: MongoDB connection string
- `JWT_SECRET`: Secret key for JWT tokens

**Frontend (.env)**
- `REACT_APP_BACKEND_URL`: Backend server URL

## 🚀 Deployment

### Backend Deployment
1. Set up your production environment variables
2. Install dependencies: `npm install --production`
3. Start the server: `npm start`

### Frontend Deployment
1. Build the production version: `npm run build`
2. Deploy the `build` folder to your hosting service

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch: `git checkout -b feature-name`
3. Commit your changes: `git commit -m 'Add feature'`
4. Push to the branch: `git push origin feature-name`
5. Submit a pull request

## 📝 License

This project is licensed under the MIT License.

## 🙏 Acknowledgments

- React.js team for the amazing framework
- Socket.io for real-time communication
- All contributors and supporters

---

⭐ Star this repository if you find it helpful!
