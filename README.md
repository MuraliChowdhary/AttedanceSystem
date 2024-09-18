 # Attendance Management System

The Attendance Management System is a real-time web application built with the MERN stack (MongoDB, Express, React, Node.js). It provides a smart, efficient way for institutions to track student attendance based on geo-location. The system includes separate functionalities for students and administrators, with a comprehensive dashboard for monitoring attendance records.

Features
Student Functionalities
Geo-location Based Attendance: Students can mark their attendance from specific locations using their mobile devices.
Profile Management: Students can create and update their profiles, including personal information and class details.
Attendance History: Students can view their attendance records, including dates and locations where attendance was marked.
Notifications: Receive real-time notifications about class schedules and attendance status.
Admin Functionalities (Dashboard)
Admin Dashboard: A central dashboard for managing students, viewing attendance records, and analyzing attendance trends.
Student Management: Add, edit, and manage student profiles and classes.
Attendance Monitoring: View real-time attendance status based on students' geo-location.
Reports & Analytics: Generate reports and statistics on student attendance for different classes, time periods, and more.
Notifications: Send notifications or reminders to students regarding attendance.
Tech Stack
Frontend: React.js, HTML5, CSS3
Backend: Node.js, Express.js
Database: MongoDB (using Mongoose for ORM)
Geo-location: Browser-based Geo-location APIs
Authentication: JSON Web Token (JWT)
Styling: CSS Frameworks (Bootstrap)
Installation and Setup
Prerequisites
Node.js (v14 or higher)
MongoDB (local installation or MongoDB Atlas)
Git
NPM or Yarn (for package management)
Steps to Install
Clone the Repository:

 
git clone https://github.com/yourusername/attendance-management-system.git
Navigate to the Project Directory:

 
cd attendance-management-system
Install Dependencies:

For the backend:
 
cd backend
npm install
For the frontend:
 
cd ../frontend
npm install
Set Up Environment Variables:

Create a .env file in the backend directory with the following variables:
makefile
Copy code
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
PORT=5000
Create a .env file in the frontend directory with:
bash
Copy code
REACT_APP_API_URL=http://localhost:5000/api
Start the Application:

Backend (from the backend directory):
 
npm run dev
Frontend (from the frontend directory):
 
npm start
Access the Application:

Open a browser and go to http://localhost:3000 to access the frontend.
The backend server runs on http://localhost:5000.
Usage
For Students
Sign Up & Log In: Register and log in with personal information and class details.
Mark Attendance: Use the "Mark Attendance" feature to log attendance based on geo-location. The system will only allow marking attendance if the student is within a predefined location range.
View Attendance History: Check previous attendance records with details like date, time, and location.
For Admin (Dashboard)
Log In: Access the admin dashboard using provided credentials.
Manage Students: Add new students, update details, and manage class information.
Monitor Attendance: View real-time attendance logs and track which students have marked their attendance.
Analytics & Reports: Generate attendance reports for specific classes and time periods to identify trends.
Send Notifications: Notify students about important updates related to attendance.
Screenshots
Dashboard:

Mark Attendance:

Attendance History:

Contributing
If you wish to contribute to this project, follow these steps:

Fork the repository.
Create a new branch (git checkout -b feature-branch).
Make changes or add new features.
Commit changes (git commit -m 'Add new feature').
Push to the branch (git push origin feature-branch).
Open a pull request.
License
This project is licensed under the MIT License. See the LICENSE file for more details.

Future Enhancements
Integration with Google Maps: Display live locations and routes on an interactive map.
Mobile App Integration: Create a mobile app for easier geo-location attendance marking.
Automated Reporting: Automatically generate and email attendance reports to administrators periodically.
Facial Recognition: Use facial recognition to enhance the attendance marking process.
Contact
For any queries or feedback, please contact:

Name:Murali
Email: muralisudireddy0@gmail.com
GitHub: MuraliChowdhary
