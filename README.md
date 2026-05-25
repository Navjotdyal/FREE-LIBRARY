# FREE-LIBRARY
An open digital library platform where users can upload, read, share, and download books, articles, newsletters, and creative content.

🚀 Project Overview

Free-Library is a full-stack MERN web application designed to make knowledge accessible to everyone.
The platform allows readers to discover content and enables independent writers/authors to publish their work online.

Users can:

Upload PDFs and digital content
Read books online
Download limited free content
Create author profiles
Share articles and newsletters
Explore educational and creative resources

The project focuses on:

Free knowledge sharing
Digital publishing
Community-driven learning
Supporting new writers and creators
✨ Features
👤 Authentication System
User Signup & Login
JWT Authentication
Password Encryption using bcrypt
Protected Routes
📚 Digital Library
Upload Books
Upload Articles
Upload Newsletters
Upload Notes & PDFs
Categorized Content
✍️ Author Profiles
Public Author Profiles
Published Content Showcase
Author Bio & Social Links
Independent Writer Support
📖 Reading System
Online PDF Reading
Responsive Reading Interface
Search & Discover Content
⬇️ Download System
Limited Free Downloads
PDF Download Management
Download Tracking
🔍 Search & Filtering
Search by:
Title
Author
Category
Keywords
🎨 Modern UI/UX
Responsive Design
Mobile Friendly
Clean Dashboard
Modern Tailwind UI
🛠️ Tech Stack
Frontend
React.js
Tailwind CSS
React Router DOM
Axios
Backend
Node.js
Express.js
Database
MongoDB
Mongoose
Authentication
JWT (JSON Web Token)
bcrypt.js
File Handling
Multer
Cloudinary / Local Storage
📂 Project Structure
Free-Library/
│
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── layouts/
│   │   ├── context/
│   │   ├── services/
│   │   └── App.jsx
│
├── backend/
│   ├── controllers/
│   ├── routes/
│   ├── middleware/
│   ├── models/
│   ├── config/
│   ├── uploads/
│   └── server.js
│
├── README.md
└── package.json
⚙️ Installation
1️⃣ Clone Repository
git clone https://github.com/your-username/free-library.git
2️⃣ Navigate to Project
cd free-library
🔥 Frontend Setup
cd frontend
npm install
npm run dev

Frontend runs on:

http://localhost:5173
🚀 Backend Setup
cd backend
npm install
npm run server

Backend runs on:

http://localhost:5000
🌐 Environment Variables

Create .env file inside backend folder:

PORT=5000

MONGO_URI=your_mongodb_connection

JWT_SECRET=your_secret_key

CLOUDINARY_CLOUD_NAME=your_cloud_name

CLOUDINARY_API_KEY=your_api_key

CLOUDINARY_API_SECRET=your_api_secret
📸 Future Features
AI Book Recommendation System
Real-Time Chat
Audio Books
E-Book Marketplace
Subscription Plans
Ratings & Reviews
Admin Dashboard
Multi-Language Support
Reading Progress Tracker
Bookmark System
Dark Mode
🎯 Main Goals
Promote free education
Support independent writers
Build a global reading community
Make digital knowledge accessible
🧠 Learning Objectives

This project helps developers learn:

Full Stack MERN Development
Authentication Systems
REST APIs
File Upload Systems
MongoDB Database Design
React Frontend Architecture
Backend API Development
🤝 Contributing

Contributions are welcome!

Fork the repository
Create a new branch
Commit your changes
Push the branch
Create a Pull Request
📜 License

This project is licensed under the MIT License.

💡 Inspiration

Inspired by the idea of making knowledge free and accessible to everyone while giving independent creators a platform to publish their work.

👨‍💻 Author

Navjot Singh

LinkedIn: Navjot Singh LinkedIn
⭐ Support

If you like this project:

⭐ Star the repository
🍴 Fork the project
📢 Share it with others
