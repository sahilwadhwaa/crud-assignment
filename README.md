# CRUD Assignment

This repository contains the code for a CRUD (Create, Read, Update, Delete) application built using MongoDB, Express,Reactjs, and Node.js. The application is designed to manage student and classroom data.
Hosted Link- https://crud-operationz.netlify.app/

## Features

- User authentication and login functionality.
- The app uses the bcrypt package and JSON Web Tokens(JWT) for authentication and authorization in the backend side and Formik and Yup in the Frontend.
- Main dashboard displaying tables for students and classrooms.
- Ability to add, edit, and delete rows in the tables.
- Dropdown list to assign students to classrooms.
- Database tables for students and classrooms.
- API endpoints for CRUD operations.
- Authentication middleware to ensure authorized access to the API.

## Installation

To run the calculator app locally, follow these steps:

1. Clone the repository:
> git clone [https://github.com/your-username/calculator-app.git](https://github.com/sahilwadhwaa/crud-assignment.git)

2. Navigate to the project directory:
> cd crud-assignment

3. Install the dependencies:
> npm install

### Front-end (React)

4. Install the dependencies:
> cd client
> npm install

5. Start the React development server:
> npm start

6. Open your browser and visit http://localhost:3000 to access the calculator app.

## Usage

1. Register a new user account or use existing credentials to log in.
2. Once logged in, you will be redirected to the main dashboard.
3. The dashboard will display two separate tables: one for students and one for classrooms. Each table will have buttons to add, edit, and delete rows.
4. To assign a student to a classroom, use the dropdown list in the student table. Select a classroom from the list, and the student will be assigned to that classroom.
5. All CRUD operations (Create, Read, Update, Delete) should be functional for the classroom table. However, there might be some bugs preventing the connection between the students table and the backend. Please note that this is a known issue, and I am actively working on resolving it.
