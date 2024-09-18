# Attendance Management System

## Overview

The **Attendance Management System** is a real-time web application built using the MERN stack (MongoDB, Express, React, Node.js). It provides an efficient way for institutions to track student attendance based on geo-location. The system includes functionalities for students and administrators, with a comprehensive dashboard for monitoring attendance records.

## Features

### Student Functionalities
- **Geo-location Based Attendance:** Students can mark their attendance from specific locations using their mobile devices.
- **Profile Management:** Create and update profiles, including personal information and class details.
- **Attendance History:** View attendance records, including dates and locations.
- **Notifications:** Receive real-time notifications about class schedules and attendance status.

### Admin Functionalities (Dashboard)
- **Admin Dashboard:** A central dashboard for managing students, viewing attendance records, and analyzing trends.
- **Student Management:** Add, edit, and manage student profiles and classes.
- **Attendance Monitoring:** View real-time attendance status based on students' geo-location.
- **Reports & Analytics:** Generate reports and statistics on student attendance.
- **Notifications:** Send notifications or reminders to students regarding attendance.

## Tech Stack
- **Frontend:** React.js, HTML5, CSS3
- **Backend:** Node.js, Express.js
- **Database:** MongoDB (using Mongoose for ORM)
- **Geo-location:** Browser-based Geo-location APIs
- **Authentication:** JSON Web Token (JWT)
- **Styling:** CSS Frameworks (Bootstrap, Material-UI)

## Installation and Setup

### Prerequisites
- Node.js (v14 or higher)
- MongoDB (local installation or MongoDB Atlas)
- Git
- NPM or Yarn (for package management)

### Steps to Install
1. **Clone the Repository:**
    ```bash
    git clone https://github.com/yourusername/attendance-management-system.git
    ```
2. **Navigate to the Project Directory:**
    ```bash
    cd attendance-management-system
    ```
3. **Install Dependencies:**
    - For the backend:
        ```bash
        cd backend
        npm install
        ```
    - For the frontend:
        ```bash
        cd ../frontend
        npm install
        ```
4. **Set Up Environment Variables:**
    - Create a `.env` file in the `backend` directory with the following variables:
        ```
        MONGO_URI=your_mongodb_connection_string
        JWT_SECRET=your_jwt_secret_key
        PORT=5000
        ```
    - Create a `.env` file in the `frontend` directory with:
        ```
        REACT_APP_API_URL=http://localhost:5000/api
        ```
5. **Start the Application:**
    - Backend (from the `backend` directory):
        ```bash
        npm run dev
        ```
    - Frontend (from the `frontend` directory):
        ```bash
        npm start
        ```
6. **Access the Application:**
    - Open a browser and go to `http://localhost:3000` to access the frontend.
    - The backend server runs on `http://localhost:5000`.

## Usage

### For Students
1. **Sign Up & Log In:** Register and log in with personal information and class details.
2. **Mark Attendance:** Use the "Mark Attendance" feature to log attendance based on geo-location.
3. **View Attendance History:** Check previous attendance records with details like date, time, and location.

### For Admin (Dashboard)
1. **Log In:** Access the admin dashboard using provided credentials.
2. **Manage Students:** Add new students, update details, and manage class information.
3. **Monitor Attendance:** View real-time attendance logs.
4. **Analytics & Reports:** Generate attendance reports for specific classes and time periods.
5. **Send Notifications:** Notify students about important updates related to attendance.

 
## Contributing
If you wish to contribute to this project, follow these steps:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make changes or add new features.
4. Commit changes (`git commit -m 'Add new feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Open a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Future Enhancements
- **Integration with Google Maps:** Display live locations and routes on an interactive map.
- **Mobile App Integration:** Create a mobile app for easier geo-location attendance marking.
- **Automated Reporting:** Automatically generate and email attendance reports to administrators.
- **Facial Recognition:** Use facial recognition to enhance the attendance marking process.

## Contact
For any queries or feedback, please contact:
- **Name:**  Murali
- **Email:** muralisudireddy0@gmail.com
- **GitHub:** [MuraliChowdhary](https://github.com/MuraliChowdhary)
