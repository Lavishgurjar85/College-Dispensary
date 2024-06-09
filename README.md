# College-Dispensary
For creating a dispensary website for locally using in the college or can be modified to used by Hospital itself


Medical Management System
Table of Contents
Introduction
Features
Technologies Used
Prerequisites
Installation
Environment Variables
Usage
API Endpoints
Contributing
License
Introduction
The Medical Management System is a web application designed to streamline the management of medical data including user authentication, doctor appointments, camps, prescriptions, hospitals, and more. This project leverages Node.js, Express, MongoDB, Passport.js for authentication, and other modern web technologies.

Features
User authentication and authorization (Patients, Doctors, Admins)
Dashboard for viewing guidelines, camps, and hospitals
Prescription management and encryption
Appointment booking system
Feedback submission
File upload for reports and guidelines
Disease prediction using Python script
Technologies Used
Node.js
Express
MongoDB
Mongoose
Passport.js
EJS (Embedded JavaScript templates)
Multer (for file uploads)
Python (for disease prediction)
Prerequisites
Before you begin, ensure you have the following installed:

Node.js
MongoDB
Python (if using disease prediction feature)
Installation
Clone the repository:
bash
Copy code
git clone https://github.com/Lavishgurjar85/College-Dispensary.git
Change to the project directory:
bash
Copy code
cd medical-management-system
Install the dependencies:
bash
Copy code
npm install
Environment Variables
Create a .env file in the root directory of the project and add the following environment variables:

makefile

Copy code
SECRET=yourSecretKey
Usage
Start the MongoDB server:
bash
Copy code
mongod
Start the Node.js server:
bash
Copy code
node app.js
Open your browser and navigate to http://localhost:3000
API Endpoints
Here is a summary of the key endpoints available in the application:

GET / - Main page
GET /dashboard - User dashboard
GET /logout - Logout
POST /register - User registration
POST /login - User login
POST /submitcamp - Submit a new camp
POST /prescriptions - Submit a new prescription
POST /predictions - Disease prediction
POST /add_hospital - Add a new hospital
POST /submitFeedback - Submit feedback
POST /upload - Upload a file
POST /guidelines-upload - Upload guidelines
GET /reports - View user reports
GET /book-appointment - View available doctors for booking
POST /addDoctor - Add a new doctor
POST /:username/book-appointment - Book an appointment
GET /view-appointments - View appointments
POST /availability - Update doctor's availability
Contributing
Contributions are welcome! Please fork this repository and submit a pull request with your changes. Make sure to follow the existing code style and include appropriate tests.
