Video Hosting Platform

A full-featured video hosting platform built with Node.js, Express.js, MongoDB, and Mongoose, designed to provide seamless video management and dynamic user interactions. This project includes user authentication, video uploads, playback, and real-time features like subscriptions and notifications.

<img width="1080" alt="Database Schema" src="https://github.com/user-attachments/assets/d52a00db-46a5-4de5-a26d-444938cb5648" />

Features
* Robust Backend Architecture: Built with Node.js and Express.js to handle user requests efficiently and integrate seamlessly with front-end services.
* Secure User Authentication: Utilizes JWT and bcrypt for enhanced security, ensuring protection of sensitive user data.
* Comprehensive Video Management: Features video uploads, playback, likes, dislikes, comments, and replies, with data efficiently stored and retrieved using MongoDB and Mongoose.
* Dynamic User Interaction: Includes subscriptions, notifications, and real-time data updates to ensure a dynamic and engaging user experience.
* Scalability and Performance: Implements industry-standard practices like access tokens, refresh tokens, and rigorous testing to ensure the platform is scalable and performs optimally.

Tech Stack
* Backend: Node.js, Express.js
* Database: MongoDB, Mongoose
* Authentication: JWT, bcrypt
* Others: Access Tokens, Refresh Tokens

Usage
Sign Up/Log In: Users can create an account and log in to the platform.
Upload Videos: Authenticated users can upload videos to the platform.
Interact with Videos: Users can like, dislike, comment, and reply to videos.
Subscribe to Channels: Users can subscribe to their favorite channels and receive notifications.


API Endpoints
POST /api/auth/signup: Register a new user
POST /api/auth/login: Log in an existing user
POST /api/videos/upload: Upload a new video
GET /api/videos/:id: Retrieve a video by ID
POST /api/videos/:id/like: Like a video
POST /api/videos/:id/dislike: Dislike a video
POST /api/videos/:id/comment: Comment on a video
POST /api/videos/:id/comment/:commentId/reply: Reply to a comment
POST /api/users/:id/subscribe: Subscribe to a channel
