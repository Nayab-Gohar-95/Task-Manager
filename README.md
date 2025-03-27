# Fullstack Task Manager (MERN)

## Overview
The **Task Manager System** is a web application designed to facilitate seamless task management for teams. Built using the **MERN stack** (MongoDB, Express.js, React, and Node.js), this platform enables users to assign, track, and collaborate on tasks efficiently. The application supports **administrators** and **regular users**, offering a structured workflow to boost productivity and organization.

## Importance
In modern work environments, managing tasks effectively is essential for productivity. Traditional methods like spreadsheets or manual tracking are inefficient and prone to errors. The **Task Manager System** addresses these issues by providing a centralized and automated platform for task management, fostering better collaboration and workflow efficiency.

## Background
With an increasing number of distributed teams and remote work setups, tools for task coordination and communication have become a necessity. The **Task Manager System** leverages modern web technologies to create an interactive and user-friendly experience. The MERN stack ensures robust performance, and the integration of **Redux Toolkit, Headless UI, and Tailwind CSS** enhances usability and responsiveness.

## **Admin Features**
1. **User Management:**
    - Create admin accounts.
    - Add and manage team members.
2. **Task Assignment:**
    - Assign tasks to individual or multiple users.
    - Update task details and status.
3. **Task Properties:**
    - Label tasks as todo, in progress, or completed.
    - Assign priority levels (high, medium, normal, low).
    - Add and manage sub-tasks.
4. **Asset Management:**
    - Upload task assets, such as images.
5. **User Account Control:**
    - Disable or activate user accounts.
    - Permanently delete or trash tasks.

## **User Features**
1. **Task Interaction:**
    - Change task status (in progress or completed).
    - View detailed task information.
2. **Communication:**
    - Add comments or chat to task activities.

## **General Features**
1. **Authentication and Authorization:**
    - User login with secure authentication.
    - Role-based access control.
2. **Profile Management:**
    - Update user profiles.
3. **Password Management:**
    - Change passwords securely.
4. **Dashboard:**
    - Provide a summary of user activities.
    - Filter tasks into todo, in progress, or completed.

## **Technologies Used**
- **Frontend:**
    - React (Vite)
    - Redux Toolkit for State Management
    - Headless UI
    - Tailwind CSS
- **Backend:**
    - Node.js with Express.js
- **Database:**
    - MongoDB for efficient and scalable data storage.

## **Setup Instructions**

### Server Setup
#### Environment Variables
Create a `.env` file in the server folder with the following values:
```sh
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
PORT=8800
NODE_ENV=development
```

### Set Up MongoDB
1. Visit MongoDB Atlas: [https://www.mongodb.com/cloud/atlas](https://www.mongodb.com/cloud/atlas).
2. Create an account and log in.
3. Set up a new cluster, configure settings, and create a database.
4. Configure the `.env` file with the MongoDB connection URL.

### Steps to Run Server
1. Open the project in your preferred editor.
2. Navigate into the server directory:
   ```sh
   cd server
   ```
3. Install dependencies:
   ```sh
   npm install
   ```
4. Start the server:
   ```sh
   npm start
   ```
   If configured correctly, you should see `Database Connected` in the terminal.

### Client Side Setup
#### Environment Variables
Create a `.env` file in the client folder with the following values:
```sh
VITE_APP_BASE_URL=http://localhost:8800
VITE_APP_FIREBASE_API_KEY=your_firebase_api_key
```

### Steps to Run Client
1. Navigate into the client directory:
   ```sh
   cd client
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Start the application:
   ```sh
   npm start
   ```
4. Open [http://localhost:3000](http://localhost:3000) in your browser to view the app.

## Future Improvements
🚀 **Real-time Notifications**  
🚀 **Task Delegation Enhancements**  
🚀 **Advanced Reporting & Analytics**  

