# English Club Web

![English Club Web](path_to_logo_image)

## Overview

English Club Web is a web application designed to help users improve their English skills. It offers a variety of resources and interactive features to make learning English fun and effective.

## Features

- **Interactive Lessons**: Engage with interactive lessons and quizzes to enhance your learning experience.
- **Community Forums**: Connect with other learners, share tips, and get your questions answered.
- **Resource Library**: Access a comprehensive library of English learning materials, including videos, articles, and exercises.
- **Progress Tracking**: Monitor your progress and set goals to stay motivated.

## Technologies Used

- **Frontend**:
  - HTML
  - CSS
  - JavaScript

- **Backend**:
  - Node.js
  - Express

- **Database**:
  - MySQL

- **Containerization**:
  - Docker

## Installation

To set up the project locally, follow these steps:

1. Clone the repository:
   - `git clone https://github.com/AlfianRamadani/english-club-web.git`

2. Navigate into the project directory:
   - `cd english-club-web`

3. Install the required dependencies for the backend:
   - `cd backend`
   - `npm install`

4. Set up the MySQL database:
   - Create a new database in MySQL (e.g., `english_club`).
   - Import the database schema from the `backend/db/schema.sql` file.

5. Configure the environment variables:
   - Create a `.env` file in the `backend` directory with the following content:
     ```
     DB_HOST=localhost
     DB_USER=root
     DB_PASSWORD=your_password
     DB_NAME=english_club
     PORT=5000
     ```

6. Start the backend server:
   - `npm start`

7. Set up the frontend:
   - Navigate to the frontend directory:
     - `cd ../frontend`
   - Install the frontend dependencies:
     - `npm install`

8. Start the frontend development server:
   - `npm start`

9. Open the web application in your browser at:
   - `http://localhost:3000`

10. (Optional) To run the application using Docker, you can build and run the containers:
    - `docker-compose up --build`

That's it! You're all set to start using the English Club Web application locally.
