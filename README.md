# StudentHub

![image](https://github.com/urvashii-b/StudentHub/assets/130129236/f2531794-b940-4b8f-8b27-cd66f41c599e)

## Description

**StudentHub** is a Database Management System project that uses Flask and MySQL to manage student-related information.

## Features

- Manage student records.
- Store information such as name, ID, courses, and grades.
- User authentication and access control.
- Search and filter functionality for student data.

## Technologies Used

- Flask: A Python web framework for building web applications.
- MySQL: A popular relational database management system.
- Other dependencies can be found in the `requirements.txt` file.

## Installation

1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/urvashii-b/StudentHub.git
   ```

2. Navigate to the project directory and create a virtual environment (optional but recommended):
   ```bash
   cd studentHub
   python -m venv venv
   ```

3. Activate the virtual environment:
   - On Windows:
     ```bash
     venv\Scripts\activate
     ```
   - On macOS and Linux:
     ```bash
     source venv/bin/activate
     ```

4. Install project dependencies:
   ```bash
   pip install -r requirements.txt
   ```

5. Create a MySQL database and configure your database connection in the `config.py` file.

6. Initialize the database:
   ```bash
   flask db init
   flask db migrate
   flask db upgrade
   ```

7. Start the application:
   ```bash
   flask run
   ```

## Usage

- Access the application by navigating to `http://localhost:5000` in your web browser.

Happy coding!


