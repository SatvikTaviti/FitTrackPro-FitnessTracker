# Health and Fitness Management Application

## Overview

This project is a comprehensive health and fitness management application developed using the MERN (MongoDB, Express, React, Node.js) stack. The application provides a user-friendly platform where individuals can register accounts, login, and manage their health and fitness goals.

## Features

- **User Registration and Login**: Users can create an account and log in securely.
- **Profile Management**: Users can update personal information such as age, height, weight, and fitness goals. Customization options include profile pictures and privacy settings.
- **Health and Fitness Goals**: Users can define various health and fitness goals, including weight management and specific workout goals.
- **Progress Tracking**: Track journey by recording measurements, workouts, and eating habits.
- **Exercise Library**: Access an extensive collection of exercises with the option to choose from predefined plans or create personal ones.
- **Workout Tracking**: Save completed exercises, set sets, reps, and weights seamlessly.
- **Stopwatch**: Maintain and measure exercise duration with an integrated stopwatch.

## Installation

### Prerequisites

- Node.js
- MongoDB

### Backend Setup

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/health-fitness-app.git
    cd health-fitness-app
    ```

2. Install backend dependencies:
    ```bash
    cd backend
    npm install
    ```

3. Set up environment variables:
    - Create a `.env` file in the `backend` directory.
    - Add the following environment variables:
    ```plaintext
    MONGODB_URI=<your_mongodb_uri>
    JWT_SECRET=<your_jwt_secret>
    ```

4. Start the backend server:
    ```bash
    npm start
    ```

### Frontend Setup

1. Install frontend dependencies:
    ```bash
    cd ../frontend
    npm install
    ```

2. Start the frontend development server:
    ```bash
    npm start
    ```

## Usage

1. Register a new account or log in with existing credentials.
2. Update your profile with personal information and set fitness goals.
3. Track your progress by recording measurements, workouts, and eating habits.
4. Explore the exercise library and design personal workout plans.
5. Save completed exercises with details on sets, reps, and weights.
6. Use the stopwatch feature to time your exercises.

## Folder Structure

```plaintext
FitTrackPro/
├── server/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   ├── config/
│   ├── .env
│   ├── server.js
│   └── package.json
├── client/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── App.js
│   │   └── index.js
│   ├── .env
│   └── package.json
├── README.md
└── package.json
