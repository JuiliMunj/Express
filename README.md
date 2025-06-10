# Express
Express Project CRUD
# Employee Management System with User Authentication

This is a Node.js + Express.js application using MongoDB and EJS templating for managing employees. It includes user registration, login, session handling, and CRUD operations for employee data with a clean UI.

## 🔧 Features

- User registration and login with session management
- Dashboard to view all employees
- Add, edit, delete employee records
- MVC architecture (Model-View-Controller)
- MongoDB for database operations
- EJS templating with reusable partials (`header`, `footer`)
- Beautiful UI with styled login and register pages

## 📁 Project Structure

DEMO/
├── app.js # Entry point
├── package.json # Project metadata and dependencies
├── controller/
│ ├── empController.js # Employee logic
│ └── userController.js # User auth logic
├── middleware/
│ └── userMiddleware.js # Auth middleware
├── model/
│ ├── empModel.js # Employee schema
│ └── userModel.js # User schema
├── router/
│ ├── empRoute.js # Employee routes
│ └── userRoute.js # User routes
├── views/
│ ├── add.ejs # Add employee page
│ ├── edit.ejs # Edit employee page
│ ├── index.ejs # Dashboard page
│ ├── login.ejs # User login page
│ ├── register.ejs # User registration page
│ └── partials/
│ ├── header.ejs
│ └── footer.ejs



## 🚀 Getting Started

### Prerequisites

- Node.js
- MongoDB (local or cloud)

### Installation

1. Clone the repository:

```bash
git clone https://github.com/yourusername/Juilimunj-express.git
cd Juilimunj-express/DEMO
```
2.Install Dependencies
npm install
```bash
npm install
```
3.Create a .env file (if needed) or update your MongoDB URI directly in the code.

4.Start your MongoDB server (locally or use MongoDB Atlas if configured).

5.Run the application:
```bash
node app.js
```
6.Open your browser and go to:

```bash
http://localhost:3000
```


## 📸 Screenshots
Registration page

![image](https://github.com/user-attachments/assets/a34b5e6b-9d1c-4a7d-b45a-1cafdf5583ec)

Login page 
![WhatsApp Image 2025-06-10 at 11 44 33 PM](https://github.com/user-attachments/assets/51741884-326f-4298-b6ec-e965bc47683a)

Add and Delete

![WhatsApp Image 2025-06-10 at 11 42 56 PM](https://github.com/user-attachments/assets/9f6531e3-3638-4a1e-9b72-d0b4b8f02f8f)


Upadate page

![WhatsApp Image 2025-06-10 at 11 43 56 PM](https://github.com/user-attachments/assets/f1863e69-53a7-4088-afaf-b3c955c6e6b1)
