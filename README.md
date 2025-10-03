
# Learning Management System (LMS)

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Screenshots](#screenshots)
- [Getting Started](#getting-started)
- [Demo Data](#demo-data)
- [Contributing](#contributing)


## Overview
The **Learning Management System (LMS)** is a full-stack web application for managing and delivering educational content. It supports user and admin roles, course creation, enrollment, subscription management, and analytics. The platform is built with React, Tailwind CSS, Node.js, Express, and MongoDB, and integrates with Cloudinary for media and Razorpay for payments.

## Features

### User
- Register and login (JWT authentication)
- Browse and enroll in courses
- View course content and lectures
- Track progress
- Manage profile

### Admin
- Create, edit, and delete courses
- Upload course content (Cloudinary)
- View analytics dashboard (users, revenue, sales)
- Visualize data with charts (Chart.js)

## Tech Stack
- **Frontend:** React, Tailwind CSS, Redux Toolkit, Chart.js, Axios
- **Backend:** Node.js, Express.js, MongoDB, Mongoose
- **Media:** Cloudinary
- **Other:** JWT, Nodemailer, Multer, React Hot Toast, React Icons

## Screenshots
---
**Home Page:**
<img width="1818" height="917" alt="image" src="https://github.com/user-attachments/assets/d80b218a-af74-4cc9-8acf-ae70399b6ef8" />

---
**Courses Page:**
<img width="1785" height="922" alt="image" src="https://github.com/user-attachments/assets/bc40535b-3eaa-4917-8abe-df8abff881ac" />


## Getting Started

### Prerequisites
- [Node.js](https://nodejs.org/) (v14.x or higher)
- [npm](https://www.npmjs.com/) (v6.x or higher)
- [MongoDB Atlas](https://www.mongodb.com/cloud/atlas) account
- [Cloudinary](https://cloudinary.com/) account


### Backend Setup
1. Clone the repository and install dependencies:
	```bash
	cd Learning-Management-System/Server
	npm install
	```
2. Create a `.env` file in the `Server` directory with your credentials:
	```env
	PORT=3000
	MONGODB_URL=your_mongodb_connection_string
	JWT_SECRET=your_jwt_secret
	CLOUDINARY_CLOUD_NAME=your_cloudinary_name
	CLOUDINARY_API_KEY=your_cloudinary_api_key
	CLOUDINARY_API_SECRET=your_cloudinary_api_secret

	...
	```
3. Start the backend server:
	```bash
	npm run dev
	```

### Frontend Setup
1. Open a new terminal and go to the client directory:
	```bash
	cd Learning-Management-System/Client
	npm install
	npm run dev
	```
2. The frontend will run on `http://localhost:5173` by default.

## Demo Data
- The frontend includes sample courses and admin dashboard data for demo purposes.
- Example user login: `muskan7512@gmail.com` / `muskan8303#`

## Contributing
Contributions are welcome! Please fork the repo and submit a pull request.




