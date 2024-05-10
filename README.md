# Student-database-management-system
The Student Database Management System (SDMS) is a comprehensive software solution designed to efficiently manage student-related information within educational institutions. Whether it's a school, college, or university, SDMS provides a centralized platform to store, organize, and access various data related to students, faculty, courses, and more.
## Installations
- Ensure that you have Node.js and npm installed in your system
- **npm install ejs --save** : to install ejs
- **npm install mysql --save** : to install mysql database
- **npm start** : to run the project
## Usage
 When you start up the project, you'll see a login screen. You can choose to log in as a teacher or a student. Depending on what you pick, you'll be taken to a different screen that suits your role. Teachers get their own tools, and students get theirs. 
## Features
### User Authentication:
- Users must log in with valid credentials (username/email and password) to access the system.
- Unauthorized users are redirected to the login page.
### Password Change (Teachers Only):
- Only teachers have the privilege to change passwords.
- Teachers can access a specific page or functionality to change passwords for themselves or other users.
### Personal Info Modification (Teachers Only):
- Only teachers have the authority to modify personal information of students.
- Teachers can access a dedicated section or form to update student information such as name, email, contact details, etc.\
### Personal Info Viewing (Students):
- Students can view their own personal information after logging in.
- This information may include details like name, email, contact number, address, etc.
### Fee Payment Status (Students):
- Students can check the status of their fee payments.
- The system displays whether the fee is paid, pending, or overdue for each student.
- This information is typically available in the student dashboard or profile page.
### Academic Performance:
- Students can view their marks and academic performance.
- The system displays a student's rank within their class based on academic performance.
- Teachers have access to view the marks and rank of all students in their respective classes.
