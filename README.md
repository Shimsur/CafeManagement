# CafeManagement

# Cafe Employee Manager

This is a full-stack application for managing cafes and employees using Nodejs on node v22.11.0 and Mysql

 It consists of two parts:

1. **Backend (API)**: A Node.js server with RESTful APIs to manage cafes and employees.
2. **Frontend (React)**: A React application that provides a user interface to interact with the backend.

## Features

- **Backend (Node.js)**:
  - **API Endpoints**:
    - `GET /cafes`: List cafes, with optional location filtering.
    - `GET /employees`: List employees in a cafe, sorted by days worked.
    - `POST /cafe`: Create a new cafe.
    - `POST /employee`: Create a new employee.
    - `PUT /cafe`: Update an existing cafe.
    - `PUT /employee`: Update an existing employee.
    - `DELETE /cafe`: Delete a cafe and all associated employees.
    - `DELETE /employee`: Delete an employee.

- **Frontend (React)**:
  - Displays cafes and employees in tables.
  - Ability to filter cafes by location.
  - Add/edit/delete cafes and employees.
  - Form validation for both cafes and employees using Material-UI components and React forms.

## Installation

### Backend Setup

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/cafe-employee-manager.git
    cd cafe-employee-manager
    ```

2. Install dependencies:

    ```bash
    npm install
    ```

3. Set up a MySQL database and configure your `.env` file with the database credentials. Example:

    ```text
    DB_HOST=localhost
    DB_USER=root
    DB_PASSWORD=your_password
    DB_NAME=cafe_employee_manager
    ```

4. Start the backend server:

    ```bash
    node server.js
    ```

    The backend will be running on `http://localhost:5000` (or whatever port you've set).

### Frontend Setup

1. In a new terminal, navigate to the `client` folder:

    ```bash
    cd client
    ```

2. Install frontend dependencies:

    ```bash
    npm install
    ```

3. Start the frontend development server:

    ```bash
    npm start
    ```

    The frontend will be running on `http://localhost:3000`.

## Usage

- The backend provides RESTful API endpoints for managing cafes and employees.
- The frontend provides a user-friendly interface to interact with the backend, including features like filtering cafes by location and managing employee records.

## Technologies Used

- **Backend**:
  - Node.js
  - Express
  - MySQL
  - Axios

- **Frontend**:
  - React.js
  - Material-UI
  - Ag-Grid
  - Axios

## Future Enhancements can be done if required

- Add authentication and authorization for users.
- Improve the UI/UX design with advanced features.

