# Web-Development-Project
# Password Manager

## Overview
The Password Manager is a full-stack web application that allows users to securely store and manage their passwords. It also provides an autofill feature for ease of use.

## Features
- User Authentication: Secure login and registration system.
- Password Storage: Save and retrieve passwords securely.
- Autofill: Automatically fill in login forms with saved credentials.
- Encryption: All passwords are encrypted before being stored in the database.

## Technologies Used
- *Frontend:*
  - HTML, CSS, JavaScript
  - React.js

- *Backend:*
  - Node.js
  - Express.js

- *Database:*
  - MongoDB

- *Authentication:*
  - JWT (JSON Web Tokens)



  ### Register
1. Navigate to the registration page.
2. Fill in your details and create an account.

### Login
1. Navigate to the login page.
2. Enter your credentials to log in.

### Store Password
1. Navigate to the password storage page.
2. Add a new entry by providing the website URL, username, and password.
3. Save the entry.

### Autofill
1. When you visit a website for which you have saved credentials, the autofill feature will suggest the saved credentials for easy login.

## Security
- All passwords are encrypted using bcrypt before being stored in the database.
- JWT tokens are used to secure authentication and authorization processes.
