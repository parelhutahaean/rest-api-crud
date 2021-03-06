# rest-api-crud

This is a simple application to create, read, update, and delete users. The application doesn't have UI so just use Postman to enter the URL.

## List of Basic Routes:

| Routes | HTTP | Description |
| --------------- | ------------- | --------------------------- |
| /api/signup | POST | Sign up as a new user |
| /api/signin | POST | Sign in to get token |
| /api/users | POST | Create a new user (role = admin only) by using token from headers |
| /api/users/ | GET | Get all users (role = admin only) by using token from headers |
| /api/users/:id | GET | Get a user by id (user can only see his own data) by using token from headers |
| /api/users/:id | PUT | Update user data by id (role = admin only) by using token from headers |
| /api/users/:id | DELETE | Delete a user by id (role = admin only) by using token from headers |

# Usage:

First after cloning the repository, install the packages needed:

npm install

Then run the application:

npm start

Access the website via http://localhost:3000 by using Postman
