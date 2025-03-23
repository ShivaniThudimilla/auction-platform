Online Auction Platform

Overview

The Online Auction Platform is a web application that allows users to create auctions, place bids, and purchase products securely. This platform ensures a user-friendly experience with real-time bidding features.

Features

🏷️ User Authentication (Login, Registration)

🔥 Create Auctions with a title, description, and starting bid

⚡ Real-Time Bidding

📜 Auction Listings with live updates

📧 Email Notifications for bid updates (Future Feature)

📊 Dashboard Analytics (Upcoming)

Tech Stack

Frontend:

⚛️ React.js with TypeScript

🎨 Bootstrap / Custom CSS for styling

🌐 React Router for navigation

Backend:

🛠 Node.js & Express.js

🗄️ MongoDB / PostgreSQL (TypeORM for ORM handling)

🔒 JWT Authentication

Installation

Prerequisites

Make sure you have Node.js and npm/yarn installed.

Steps to Run the Project

Clone the Repository

git clone https://github.com/ShivaniThudimilla/online-auction-platform.git
cd online-auction-platform

Install Dependencies

npm install

Start the Frontend

npm start

Runs the frontend at http://localhost:3000.

Start the Backend

cd backend
npm install
npm run dev

Runs the backend at http://localhost:5000.

API Endpoints

Authentication

POST /api/auth/register - Register a new user

POST /api/auth/login - Login and receive a JWT

Auctions

GET /api/auctions - Fetch all auctions

POST /api/auctions - Create a new auction

GET /api/auctions/:id - Get auction details

POST /api/auctions/:id/bid - Place a bid

Contributing

Want to contribute? 🚀

Fork the repository

Create a new feature branch

Submit a Pull Request

🚀 Happy Bidding! 🎉

