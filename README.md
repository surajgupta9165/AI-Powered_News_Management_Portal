# 📰 AI-Powered News Management Portal

## 📌 Overview

This AI-driven News Management Portal is designed to automate news aggregation, categorization, and recommendation using machine learning techniques. The platform provides real-time news updates, smart recommendations, and an intuitive user interface for an enhanced news consumption experience.

## ✅ Features

- 📰 Automated news aggregation from multiple sources
- 🤖 AI-powered news categorization and recommendation
- 🔍 Advanced search and filtering options
- 👥 User authentication and profile management
- 📊 Analytics dashboard for insights and trends
- 📡 Real-time updates with push notifications
- 🌙 Dark mode support for better readability

## 🛠 Tech Stack

### 📂 Backend

- 🟢 Node.js
- ⚡ Express.js
- 🗄 MongoDB (Mongoose)
- 🔐 JWT Authentication
- 🔄 Web Scraping & API integration
- 🤖 AI models for news classification

### 🎨 Frontend

- ⚛️ React.js
- 🛠 Redux Toolkit for state management
- 🎨 TailwindCSS for styling
- 🚏 React Router for navigation
- 🔗 Axios for API requests

## 📥 Installation and Setup

### ⚙️ Prerequisites

Ensure you have the following installed:

- 🔵 Node.js (v14+)
- 🗃 MongoDB
- 🧠 Python (for AI models, if applicable)

### ⚙️ Backend Setup

1. 📥 Clone the repository:
   ```sh
   git clone https://github.com/your-repo/news-portal.git
   cd news-portal/backend
   ```
2. 📦 Install dependencies:
   ```sh
   npm install
   ```
3. 🔧 Configure environment variables:
   - Create a `.env` file in the backend root directory.
   - Add the following variables:
     ```env
     PORT=5000
     MONGODB_URI=your-mongodb-uri
     JWT_SECRET_KEY=your-secret-key
     NEWS_API_KEY=your-api-key
     ```
4. 🚀 Start the server:
   ```sh
   npm start
   ```

### ⚙️ Frontend Setup

1. 📂 Navigate to the frontend directory:
   ```sh
   cd ../frontend
   ```
2. 📦 Install dependencies:
   ```sh
   npm install
   ```
3. 🚀 Start the frontend:
   ```sh
   npm start
   ```
4. 🌐 Open `http://localhost:3000` in your browser.

## 🎯 Running the Application

- ▶️ Start the backend server (`npm start` in `backend` folder)
- ▶️ Start the frontend (`npm start` in `frontend` folder)
- ✅ The application should now be running at `http://localhost:3000`

## 🔗 API Endpoints

- 📝 `POST /api/v1/user/register` - User registration
- 🔑 `POST /api/v1/user/login` - User login
- 📰 `GET /api/v1/news` - Fetch news articles
- 📊 `GET /api/v1/trends` - Get trending news insights

## 🤖 AI Functionalities

- 📌 Categorization: Automatically classifies news articles into categories
- 🔥 Trending Analysis: Detects trending news topics
- 🎯 Personalization: Recommends news based on user preferences

## 👨‍💻 Author

Developed by Suraj Gupta ✨

