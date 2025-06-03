
# FullStack Job Portal App (MERN Stack)

This project is a FullStack Job Portal Application built using the MERN stack, as demonstrated in the [YouTube tutorial](https://youtu.be/F5EYXc91Cpo?si=hQww7ysUJnfUAIj8). The application allows users to register, log in, and apply for jobs, while administrators can post job listings and manage applications.

## Features

- **User Authentication**: Secure registration and login functionality.
- **Job Listings**: View and search for available job postings.
- **Job Application**: Apply to jobs directly through the platform.
- **Admin Dashboard**: Administrators can post new jobs and manage existing listings.
- **Responsive Design**: Optimized for both desktop and mobile devices.

## Technologies Used

- **Frontend**:
  - React.js
  - React Router
  - Axios
  - Bootstrap (or Tailwind CSS)

- **Backend**:
  - Node.js
  - Express.js
  - MongoDB
  - Mongoose
  - JSON Web Tokens (JWT)
  - bcrypt.js

## Installation and Setup

1. **Clone the repository**:

   ```bash
   git clone https://github.com/yourusername/job-portal-app.git
   cd job-portal-app


2. **Install server dependencies**:

   ```bash
   cd server
   npm install
   ```

3. **Set up environment variables**:

   Create a `.env` file in the `server` directory and add the following:

   ```env
   PORT=5000
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret
   ```

4. **Start the server**:

   ```bash
   npm run server
   ```

5. **Install client dependencies**:

   ```bash
   cd ../client
   npm install
   ```

6. **Start the client**:

   ```bash
   npm start
   ```

   The application will be running at `http://localhost:3000`.

## Folder Structure

```
job-portal-app/
├── client/           # React frontend
├── server/           # Express backend
├── README.md
```
