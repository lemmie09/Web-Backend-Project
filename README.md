# Projecter

Projecter is a backend application for managing projects, tasks, and user roles. It enables an Admin to create and assign Project Managers (PMs) for projects, who can then add tasks and assign them to registered users. The application is designed with a robust role-based user management system, ensuring seamless collaboration and project organization.

## Features

1. Role-Based Access Control:
     Admin:
     - Create and manage projects.
     - Assign Project Managers (PMs) to projects.
     - Change user roles (e.g., promote a User to PM).
     Project Manager (PM):
     - Add tasks to their assigned projects.
     - Assign tasks to Users.
     Employee (User):
     - View their assigned tasks.
     - Update the status of their tasks.
   - Default role for new sign-ups is `User`.

2. User Registration and Authentication:
   - User registration through the sign-up page.
   - Authentication via a secure login system.

3. Project and Task Management:
   - Admin can create and assign projects.
   - PMs can create, edit, and assign tasks within their projects.
   - Employees can view and manage their tasks.

4. Predefined Admin Account:
   - The application comes with a predefined Admin account specified in the environment file.

## Tech Stack

- Backend Framework: Node.js (Express.js)
- Database: MongoDB
- Authentication: JSON Web Tokens (JWT)
- Environment Variables Management: dotenv

