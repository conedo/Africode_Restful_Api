Africode_Restful_Api

Overview This project demonstrates the implementation of a RESTful API using Flask, SQLAlchemy, and other supporting libraries. The API supports basic CRUD (Create, Read, Update, Delete) operations and is designed for managing a simple user database.

Features

User Registration and Authentication CRUD Operations for Users Secure Password Handling Email Notifications

Technologies Used

Flask: Micro web framework for Python SQLAlchemy: SQL toolkit and ORM Flask-Bcrypt: Password hashing Flask-Login: User session management Flask-Mail: Sending emails

Installation

Clone the repository:

bash Copy code git clone https://github.com/yourusername/your-repo-name.git cd your-repo-name Create a virtual environment and activate it:

bash Copy code python3 -m venv venv source venv/bin/activate Install the required packages:

bash Copy code pip install -r requirements.txt

Set up the database:

bash Copy code flask db upgrade Run the application:

bash Copy code flask run

Endpoints

GET /users: Retrieve all users GET /users/: Retrieve a specific user by ID POST /users: Create a new user PUT /users/: Update an existing user by ID DELETE /users/: Delete a user by ID

Configuration

Configure your environment variables for email settings and database URI in the .env file.
