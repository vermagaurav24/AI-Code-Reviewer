AI Code Reviewer
Overview
AI Code Reviewer is a full-stack web application that utilizes the Google Gemini API to analyze and review up to 10,000 lines of code at a time. Built with the MERN stack (MongoDB, Express, React, Node.js), it provides intelligent code feedback, best practices, and suggestions for optimization.

Features
✅ AI-Powered Code Review – Analyzes large codebases using Google Gemini API
✅ MERN Stack – Full-stack application with MongoDB, Express, React, and Node.js
✅ Syntax & Best Practices Suggestions – Detects issues in syntax, structure, and performance
✅ Code Optimization & Refactoring – Offers AI-powered recommendations
✅ Multi-Language Support – Supports multiple programming languages
✅ User Authentication – Secure login & signup using JWT
✅ Dark/Light Mode – Customizable UI for better readability

Tech Stack
Frontend: React, Tailwind CSS
Backend: Node.js, Express.js
Database: MongoDB
Authentication: JWT (JSON Web Token)
AI Integration: Google Gemini API
Deployment: Vercel (Frontend), Render/Heroku (Backend)
Installation & Setup
1️⃣ Clone the Repository
bash
Copy
Edit
git clone https://github.com/vermagaurav24/AI-Code-Reviewer.git
cd AI-Code-Reviewer
2️⃣ Install Dependencies
Frontend:

bash
Copy
Edit
cd frontend
npm install
npm start
Backend:

bash
Copy
Edit
cd backend
npm install
nodemon server.js
3️⃣ Setup Environment Variables
Create a .env file in the backend folder and add:

plaintext
Copy
Edit
MONGO_URI=your_mongodb_connection_string
GOOGLE_GEMINI_API_KEY=your_google_gemini_api_key
JWT_SECRET=your_jwt_secret
4️⃣ Start the Application
bash
Copy
Edit
npm run dev
Your AI Code Reviewer will be live at http://localhost:3000 🎉

API Endpoints
Method	Endpoint	Description
POST	/api/review	Analyze and review code using AI
POST	/api/auth/signup	Register a new user
POST	/api/auth/login	Authenticate a user
GET	/api/user/profile	Fetch user profile
