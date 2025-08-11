## Mini WhatsApp Clone
A lightweight WhatsApp-style chat application built with Node.js, Express, MongoDB (Mongoose), and EJS.
Supports creating, viewing, editing, and deleting chats with a clean WhatsApp-like UI.

# Features
  - Create new chats
  - View all chats in a WhatsApp-style UI
  - Edit existing chats
  - Delete chats using method override
  - Auto-scroll to latest messages
  - Simple but responsive design

# Tech Stack
Backend: Node.js, Express.js
Frontend: EJS, CSS
Database: MongoDB, Mongoose
Others: method-override, body-parser

# Installation
1. Clone the repository
git clone https://github.com/<your-username>/mini-whatsapp-clone.git
2. Go to project directory
cd mini-whatsapp-clone
3. Install dependencies
npm install
4. Start MongoDB (make sure it's running locally)
mongod
5. Run the app
node inedx.js

# Configuration
By default, the app connects to:
mongodb://127.0.0.1/whatsapp
You can change this in index.js if needed.
