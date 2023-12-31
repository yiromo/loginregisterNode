Passport Authentication System
This is a simple authentication system using Passport.js, Express, bcrypt, and PostgreSQL for user registration and login.

Setup
Clone the repository:

bash
Copy code
git clone <[repository_url](https://github.com/yiromo/loginregisterNode)>
Install dependencies:

Copy code
npm install
Set up your environment variables:

Create a .env file in the root directory.

Add the following variables:

makefile
Copy code
PORT=3000
SESSION_SECRET=Your_Session_Secret_Here
DATABASE_URL=Your_Database_URL_Here
Database Setup:

Create a PostgreSQL database.
Update the dbConfig.js file with your database credentials.
Run the application:

sql
Copy code
npm start
Usage
Visit http://localhost:3000 in your browser to access the application.
Routes
/ - Home page
/users/register - User registration page
/users/login - User login page
/users/dashboard - User dashboard page (accessible after login)
/users/logout - Log out the current user
Notes
The application uses Passport.js for authentication and bcrypt for password hashing.
Ensure proper error handling and validation for production use.
Contributing
Contributions are welcome! Please fork the repository and create a pull request for any suggested improvements or features.

License
This project is licensed under the MIT License.
