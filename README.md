# 💬 Full Stack Chat Application

A real-time full stack chat application built using the **MERN stack (MongoDB, Express.js, React.js, Node.js)** with **Socket.io** for instant messaging. This project showcases core concepts of full stack development, including authentication, real-time WebSockets, cloud deployment, and responsive UI design.

## 🚀 Features

- 🔐 **Authentication**: JWT-based login and registration with secure password hashing.
- 💬 **Real-Time Messaging**: Seamless bi-directional communication using WebSockets via Socket.io.
- 🧑‍🤝‍🧑 **User Management**: Create group chats, add/remove users, and manage conversations.
- 📱 **Responsive UI**: Built with **React.js** and **Tailwind CSS**, optimized for both desktop and mobile.
- ☁️ **Cloud Deployment**: Hosted using **Render**, **MongoDB Atlas**, and **Vercel** for scalability.
- 📦 **Image Uploads**: Integrated **Cloudinary** for user profile picture uploads.

## 🖥️ Tech Stack

- **Frontend**: React.js, Tailwind CSS, Axios
- **Backend**: Node.js, Express.js, MongoDB, Socket.io
- **Authentication**: JWT, bcrypt
- **Cloud & Hosting**: MongoDB Atlas, Vercel (Frontend), Render (Backend), Cloudinary (Image Storage)

## 🔗 Live Demo & Source Code

- 🔗 **Live App**: [Chat App Live](https://full-stack-chat-app-8ps2.onrender.com)
- 💻 **GitHub Repository**: [GitHub Repo](https://github.com/anvay936/full-stack-chat-app)

## ⚙️ Setup Instructions

### 1. Clone the repository
```bash
git clone https://github.com/anvay936/full-stack-chat-app
cd full-stack-chat-app
```

### 2. Install dependencies
```bash
npm install
cd frontend
npm install
cd ..
```
### 3. Setup enviroment variables

**Create a .env file in the root directory and add:**
```js
MONGODB_URI=your_mongo_db_uri
PORT=5001
JWT_SECRET=your_jwt_secret

CLOUDINARY_CLOUD_NAME=your_cloudinary_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret

NODE_ENV=development
```
### 4. Start the development servers

**In one terminal:**
```bash
npm run server
```
**In another terminal:**
```bash
cd frontend
npm start
```

**🛠️ Build the App for Production**
```bash
npm run build
```

## 🧠 Learnings & Challenges

- Gained experience with Socket.io for real-time bi-directional communication.
- Integrated JWT authentication with React and Express securely.
- Deployed frontend and backend on different platforms and handled CORS and proxy issues.
- Worked with Cloudinary API for image handling.

## 📞 Contact

- Email: anvay936@gmail.com
- [LinkedIn](https://www.linkedin.com/in/anvay-sawai-ab14771b0/)

