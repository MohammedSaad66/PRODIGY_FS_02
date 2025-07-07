Goal:
Build a web app that lets an admin Create, Read, Update, and Delete (CRUD) employee records — securely and with authentication.

✨ Features to Implement
✅ Authentication
Only logged-in admins can manage employees
Reuse your login system from Task 1

✅ CRUD for Employees
Add new employee
View list of employees
Edit employee info
Delete employee

✅ Employee Fields (example fields)
Name
Email
Position
Department
Salary
✅ Validation
No empty fields
Email must be valid
Salary must be a number
✅ Security
Protect routes so only logged-in users can access employee management pages
Store data safely in your SQLite database
✅ Tech Stack
Node.js
Express.js
EJS for templates
SQLite3
express-session
bcrypt.js (if you want to support multiple admin users)
