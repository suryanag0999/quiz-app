Quiz App – MERN Full Stack
An interactive and responsive Quiz Application built using the MERN stack (MongoDB, Express, React, Node), styled with Tailwind CSS, and enhanced with shhad-cn for screen state control and react-toastify for elegant notifications.

 Features
Multiple categories & dynamic questions
Start, active, and result screens managed via shhad-cn
Real-time quiz validation
User login & authentication (JWT)
MongoDB-backed question & result storage
Toast notifications with react-toastify
Timer-based questions (optional)
Fully responsive UI using Tailwind CSS
🛠️ Tech Stack
Frontend	Backend	Database	Styling	Utils & Libraries
React.js	Node.js	MongoDB	Tailwind CSS	shhad-cn, react-toastify
Axios	Express.js	Mongoose		JWT, dotenv
Folder Structure
Setup Instructions
Prerequisites
Node.js
MongoDB
npm / yarn
Clone & Install
git clone https://github.com/suryanag0999/quiz-app.git
cd quiz-app
In both /client/.env and /server/.env, include:

ini
Copy
Edit

 server/.env
PORT=5000
MONGO_URI=your_mongo_uri
JWT_SECRET=supersecret

# client/.env
VITE_API_URL=http://localhost:5000/api
