# Flask Registration & Login App

A secure Flask-based web application that allows users to **register and login**. The app includes **CSRF protection, password hashing, input sanitization, login attempt limiting**, and is ready for **deployment on Render**.

---

## Features

- **User Registration**  
  - Name, Email, Password input  
  - Password must be at least 6 characters with letters and numbers  

- **User Login**  
  - Validates credentials with hashed passwords  
  - Limits login attempts per email to prevent brute-force attacks  

- **Security**  
  - CSRF protection using Flask-WTF  
  - Input sanitization using Bleach  
  - HTTPS enforcement using Flask-Talisman  
  - Rate limiting and login attempt tracking  

- **Database**  
  - SQLite for storing user information  
  - Users table: `id`, `name`, `email`, `password`  
  - Attempts table for login attempt tracking  

- **Styling**  
  - External CSS for a clean, modern UI  
  - Responsive and centered forms  

---

## Folder Structure

