# Chat-App
Real-Time Chat App
This is a simple real-time chat application built using Node.js, Express, Socket.IO, and vanilla HTML, CSS, and JavaScript. Multiple users can join and chat live through WebSockets.

🔧 Features
Real-time bi-directional chat using Socket.IO

Basic front-end with HTML/CSS/JS

Node.js + Express server

Auto-reload on changes with Nodemon (dev mode)

🚀 Getting Started
Follow these steps to set up and run the project on your local machine.

📁 1. Clone the Repository
bash
Copy
Edit
git clone https://github.com/Akshattermux/Chat-App.git
cd chat-app
📦 2. Initialize Node Project
bash
Copy
Edit
npm init -y
This will create a package.json file with default values.

📥 3. Install Dependencies
bash
Copy
Edit
npm install express socket.io
Optional (for development):
Install Nodemon to auto-restart your server when files change:

bash
Copy
Edit
npm install --save-dev nodemon
🧪 4. Create Project Structure
Example structure:

pgsql
Copy
Edit
chat-app/
│
├── public/
│   ├── index.html
│   ├── style.css
│   └── script.js
│
├── server.js
├── package.json
└── README.md
🖥️ 5. Example Start Scripts
In your package.json, under "scripts", add:

json
Copy
Edit
"scripts": {
  "start": "node server.js",
  "dev": "nodemon server.js"
}
▶️ 6. Run the Server
Production Mode:
bash
Copy
Edit
npm start
Development Mode (with auto-restart):
bash
Copy
Edit
npx nodemon server.js
Or, if installed globally:

bash
Copy
Edit
nodemon server.js
🔗 Open in Browser
After starting the server, open:

arduino
Copy
Edit
http://localhost:3000
