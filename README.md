# Quiz Application using MERN

This is a full-stack quiz application built using the MERN stack (MongoDB, Express.js, React.js, and Node.js). It allows users to securely sign up and log in, create and manage quizzes, attempt them in real time, and receive instant score evaluations. The application also includes a leaderboard and performance analytics to track user progress. With JWT-based authentication, a dynamic React.js frontend, and a robust Node.js and Express.js backend, this project provides an interactive and scalable solution for conducting quizzes, making it ideal for educational and assessment purposes.

## Features

- **User Authentication:** Secure login and signup system using JWT.
- **Quiz Creation and Management:** Admins can create and manage quizzes.
- **Quiz Attempt and Evaluation:** Users can take quizzes and get real-time feedback.
- **Leaderboard & Performance Analytics:** Tracks user scores and rankings.

## Technologies Used

- **Frontend:** React.js
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Authentication:** JSON Web Token (JWT)

## Installation and Setup

### Prerequisites

Ensure you have the following installed:

- Node.js
- MongoDB
- npm or yarn

### Steps to Run the Project

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/Nagul71/QuizApplication-using-MERN.git
   cd QuizApplication-using-MERN
   ```

2. **Install Dependencies:**

   - Backend:
     ```bash
     cd backend
     npm install
     ```
   - Frontend:
     ```bash
     cd ../frontend
     npm install
     ```

3. **Configure Environment Variables:**

   - Create a `.env` file in the `backend` directory and add the required environment variables such as database connection string and JWT secret.

4. **Start the Application:**

   - Start the backend:
     ```bash
     cd backend
     npm start
     ```
   - Start the frontend:
     ```bash
     cd ../frontend
     npm start
     ```

5. **Access the Application:**

   - The frontend will be available at `http://localhost:3000`
   - The backend will run on `http://localhost:5000`

## Contributing

Contributions are welcome! Feel free to fork the repository, make improvements, and submit a pull request.


## Contact

For any issues or suggestions, open an issue in the repository.

