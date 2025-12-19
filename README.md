#Zerodha Clone – Full Stack Web Application

A full-stack clone of the Zerodha trading platform built using React, Node.js, Express, and MongoDB.
This project demonstrates a complete real-world workflow including frontend landing pages, a user dashboard, and a backend API, developed using branch-wise incremental Git workflow.

#🚀 Features
🔹 Landing Website (Frontend)

Responsive Navbar and Footer

Home, About, Products, Pricing pages

Support and Signup pages

Component-based React architecture

React Router for navigation

#🔹 User Dashboard

Interactive dashboard UI

Holdings, Orders, Positions, Funds views

Watchlist with real-time style layout

Charts and graphs (Chart.js)

Modular and reusable React components

#🔹 Backend (API Layer)

Express.js server

MongoDB integration using Mongoose

Schemas and models for:

Holdings

Orders

Positions

REST-ready backend structure

Environment variables secured using .env

#🛠️ Tech Stack

Frontend

React.js

JavaScript (ES6)

CSS

React Router

Dashboard

React.js

Chart.js

Context API

Backend

Node.js

Express.js

MongoDB

Mongoose

Tools

Git & GitHub

npm

VS Code

#📂 Project Structure
Zerodha-clone/
│
├── frontend/          # Landing website (React)
│
├── dashboard/         # User dashboard UI (React)
│
├── backend/           # Backend server (Node + Express)
│   ├── models/
│   ├── schemas/
│   ├── index.js
│
├── .gitignore
├── README.md
└── package.json


#🔄 Git Workflow (Important)

This project was developed using a feature-branch based Git workflow:

main – stable production branch

Feature branches:

layout-setup

home-page

about-page

products-page

pricing-page

support-page

signup-page

dashboard-ui

backend-setup

Each feature was:

Developed in its own branch

Committed with meaningful messages

Merged cleanly into main

This reflects real-world industry Git practices.

#⚙️ How to Run the Project Locally
##1️⃣ Clone the Repository
git clone https://github.com/<your-username>/Zerodha-clone.git
cd Zerodha-clone

##2️⃣ Run Frontend (Landing Website)
cd frontend
npm install
npm start


Runs on: http://localhost:3000

##3️⃣ Run Dashboard
cd dashboard
npm install
npm start


Runs on: http://localhost:3001 (or next available port)

##4️⃣ Run Backend
cd backend
npm install
node index.js


##⚠️ Create a .env file in backend/ with:

MONGO_URI=your_mongodb_connection_string
PORT=8080

#🎯 Learning Outcomes

Practical understanding of React component architecture

Dashboard-style UI development

REST API design using Express

MongoDB schema modeling with Mongoose

Professional Git & GitHub workflow

Real-world full-stack project structuring

#👨‍💻 Author

##Ayush Nimbhorkar
Full-Stack Developer (MERN)
GitHub: https://github.com/AyushNimbhorkar37

📌 Note

This project is built for educational and learning purposes as part of a web development course.
