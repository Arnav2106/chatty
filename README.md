# 💬 Realtime Chat App

![App Screenshot](/frontend/public/screenshot-for-readme.png)

I developed this full-stack realtime chat application to provide a seamless and modern messaging experience. Utilizing the MERN stack along with Socket.io for instant communication, this project features a polished UI and robust state management.

## ✨ Key Features

- 🔐 **Secure Authentication**: Full JWT-based auth and route protection.
- ⚡ **Real-time Messaging**: Instant message delivery using Socket.io.
- 🟢 **Live Status**: Real-time tracking of online/offline users.
- ☁️ **Media Uploads**: Profile picture and image sharing integrated with Cloudinary.
- 🎨 **Dynamic Themes**: 30+ themes available via DaisyUI and TailwindCSS.
- 📱 **Responsive Design**: Optimized for all screen sizes.

## 🛠️ Tech Stack

- **Frontend**: React.js, TailwindCSS, DaisyUI, Lucide React
- **State Management**: Zustand
- **Backend**: Node.js, Express.js
- **Database**: MongoDB Atlas
- **Real-time**: Socket.io
- **Storage**: Cloudinary

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/Arnav2106/chat-app.git
cd chat-app
```

### 2. Configure Environment Variables
Create a `.env` file in the `backend` directory:

```env
MONGODB_URI=your_mongodb_uri
PORT=5001
JWT_SECRET=your_secret_key
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
NODE_ENV=development
```

### 3. Install & Build
```bash
npm run build
```

### 4. Start the Application
```bash
npm start
```

## 📜 License
Licensed under the [ISC License](LICENSE).

---
Built with ❤️ by [Arnav](https://github.com/Arnav2106)
