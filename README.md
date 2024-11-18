

# CRUD

A web-based **CRUD** application built with **Node.js**, **MySQL**, **React**, and **Vite**. The app allows administrators to manage employee records, while employees can view their profile, che, and update their status.

## Table of Contents

1. [Project Description](#project-description)
2. [Technologies Used](#technologies-used)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Features](#features)


## Project Description

The **CRUD** is a modern web application that simplifies HR operations for organizations. Admins can manage employee details, while employees can manage their own profiles and tasks. The app uses **Node.js** for the backend, **React** for the frontend, and **MySQL** for storing employee and task data.

This app is built with **Vite** for fast, modern front-end development with React.

## Technologies Used

- **Frontend**: React, Vite (for bundling and fast development)
- **Backend**: Node.js, Express.js
- **Database**: MySQL
- **Authentication**: JWT (JSON Web Tokens)
- **State Management**: React Context (or optional Redux)


## Installation

Follow these steps to set up the app on your local machine.

### Prerequisites

- **Node.js** (v14 or higher)
- **npm** (Node Package Manager)
- **MySQL** (or use a cloud MySQL database such as AWS RDS)

### Steps to Install

#### 1. Clone the Repository

```bash
git clone https://github.com/Umeshkhetra/CRUD.git
```

#### 2. Navigate to the Project Directory

```bash
cd server
```

#### 3. Install Backend Dependencies

Navigate to the **server** directory and install the necessary dependencies:

```bash
cd server
npm install
```

#### 4. Install Frontend Dependencies

Navigate to the **client** directory and install the necessary dependencies:

```bash
cd client
npm install
```

#### 5. Set Up MySQL Database

1. Log in to MySQL:

```bash
mysql -u root -p
```

2. Create a new database for the application:

```sql
CREATE DATABASE employeems;
```
CREATE SCHEMA 
1 admin - id , email , password.
2 category - id , name.
3 employee - id, name, email, password,salary, address, image, category_id.


#### 7. Run the Backend Server

Navigate to the **server** directory and start the Node.js server:

```bash
cd server
npm start
```

The backend will run on `http://localhost:3000`.

#### 8. Run the Frontend Server

Navigate to the **client** directory and start the React app with Vite:

```bash
cd client
npm run dev
```

The React app will run on `http://localhost:5173/`.

-THANK YOU
#### LOGIN PAGE 

              ![Vite + React and 6 more pages - Personal - Microsoft​ Edge 18-11-2024 12_28_52](https://github.com/user-attachments/assets/c216f26d-b47f-4258-b467-c8a9f7be6c9d)

              ![Vite + React and 6 more pages - Personal - Microsoft​ Edge 18-11-2024 12_28_57](https://github.com/user-attachments/assets/e5e95192-ee89-48e3-bf06-5d6adae7e56d)

