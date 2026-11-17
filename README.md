# ZCoder

ZCoder is a collaborative coding platform designed to help users practice, bookmark, and discuss coding problems in real time. This repository contains the backend codebase built using Node.js, Express.js, MongoDB, and Mongoose.

## Features

- **User Authentication:** Secure JWT-based authentication and password hashing with `bcryptjs`.
- **RESTful APIs:** Comprehensive endpoints for user, problem, and bookmark management.
- **Database Models:** Structured Mongoose schemas for users, coding problems, and chat messages.
- **Real-Time Chat:** Instant messaging and live problem discussions powered by WebSockets (`Socket.io`).
- **MongoDB Integration:** Cloud database persistence via MongoDB Atlas and Mongoose.
- **Organization & Collaboration:** Full support for problem tagging, personal notes, and user contributions.

## Tech Stack

- **Runtime:** Node.js
- **Framework:** Express.js
- **Database:** MongoDB (Atlas) & Mongoose
- **Real-Time Communication:** Socket.io
- **Security & Auth:** `jsonwebtoken` (JWT) & `bcryptjs`

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org) installed on your machine
- A [MongoDB Atlas](https://mongodb.com) cluster or local MongoDB instance

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com
   cd Zcoder
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Set up environment variables:**
   Create a `.env` file in the root directory and add your configuration:
   ```env
   PORT=5000
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret_key
   ```

4. **Start the server:**
   ```bash
   npm start
   ```
