# EmployeeReviewSystem

The hoisted link leads to a full-stack employee review application with various features

Description:
The application allows an admin user to manage and review employees based on their work performance. The admin has special privileges to assign employees as reviewers and reviewees. The admin can also appoint new admins, add new employees to the system, and remove existing employees. All reviews given by employees are stored in the database.

Tech Stack: 
The application is built using the following technologies:
•	Node.js
•	Express.js
•	MongoDB (for database)
•	EJS (Embedded JavaScript) for templating
•	JavaScript for client-side interactions
•	HTML and CSS for frontend design

Setup Instructions:
To set up the project on your local system, follow these steps:
•	Clone the project repository to your local machine.
•	Ensure you have Node.js and npm (Node Package Manager) installed.
•	Navigate to the project directory using the terminal or command prompt.

Run the following commands to install dependencies and start the server:
npm install
npm start

Alternatively, you can use nodemon for automatic server restart on code changes:
nodemon index.js

Admin Privileges: 
To assign an employee as an admin, use the secret key: "happy."

Features:
•	Employee Review: Employees can review each other's work performance.
•	Admin Privileges: The admin can assign tasks, remove employees, add new employees, and appoint new admins.
•	Review Storage: All reviews given by employees are stored securely in the database.

In summary, the app facilitates a comprehensive employee review system managed by an admin, where reviews and performance-related tasks can be assigned and monitored efficiently.

# HomePage / Admin View

  # Home page / Employee view

  
  # Sign-Up


  # Sign-In

  # Forget Password
  
  # Assign Task

  # Employee List
  

  

### Folder Structure

```
Employee Review System
    |
    |               |--->css
    |--->assets---->|--->images
    |             
    |
    |               |--->flashMiddleware.js
    |--->config---->|--->mongoose.js
    |               |--->passport-local-Stradegy.js
    |
    |                  |-->admin_controller.js
    |--->controllers-->|-->home_controller.js
    |                  |-->review_controller.js
    |                  |-->user_controller.js
    |
    |               |-->review.js
    |--->models---->|
    |               |-->user.js
    |
    |              
    |               |-->admin.js
    |--->routes---->|-->index.js
    |               |-->review.js
    |               |-->user.js
    |
    |              |--->_header.ejs
    |              |---> addEmployee.ejs
    |              |---> admin.ejs
    |              |---> employe.ejs
    |--->views---->|--->forget_password.ejs
    |              |--->home.ejs
    |              |--->layout.ejs
    |              |--->sign_in.ejs
    |              |--->sign_up.ejs
    |
    |-->node_modules
    |-->.gitignore
    |--> index.js
    |--> package-lock.json
    |-->package.json
    
    ````
