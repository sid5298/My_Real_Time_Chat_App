This is a comprehensive real-time communication application designed for messaging and video calls.

Features & Highlights
Real-time Messaging with Typing Indicators & Reactions

1-on-1 and Group Video Calls with Screen Sharing & Recording

JWT Authentication & Protected Routes

Language Exchange Platform with 32 Unique UI Themes

Tech Stack: React + Express + MongoDB + TailwindCSS + TanStack Query

Global State Management with Zustand

Error Handling (Frontend & Backend)

Free Deployment

Built with Scalable Technologies like Stream

And much more!

Get Started
To run this application on your local machine, you'll need to set up both the backend and the frontend.

🧪 .env Setup
Before running the application, you'll need to create .env files in both the backend and frontend directories and populate them with your respective keys and configurations.

Backend (/backend)

Create a file named .env in the backend folder with the following content:

PORT=5001
MONGO_URI=your_mongo_uri
STREAM_API_KEY=your_stream_api_key
STREAM_API_SECRET=your_stream_api_secret
JWT_SECRET_KEY=your_jwt_secret
NODE_ENV=development

Frontend (/frontend)

Create a file named .env in the frontend folder with the following content:

VITE_STREAM_API_KEY=your_stream_api_key

🔧 Run the Backend
Navigate to the backend directory in your terminal:

cd backend

Install the backend dependencies:

npm install

Start the backend server:

npm run dev

💻 Run the Frontend
Open a new terminal window (keep the backend terminal running).

Navigate to the frontend directory:

cd frontend

Install the frontend dependencies:

npm install

Start the frontend development server:

npm run dev
