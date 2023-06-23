# Node.js Authentication Boilerplate

This is a mini Node.js project that demonstrates user authentication using middleware and provides the ability to add and remove users.

## Features

- User authentication using middleware
- User registration and login functionality
- Ability to add new users
- Ability to remove existing users

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Rutwij-Patil/node_authentication_boilerplate.git
2. Navigate to the project directory:
   ```bash
      cd node_authentication_boilerplate/node-auth
3. Install the dependencies:
   ```bash
      npm install
## Usage
1. Start the server:
   ```bash
         npm start
2. Open a New Terminal from the top menu. Test an endpoint to retrieve these users
   ```bash 
      curl localhost:5500/user

## API Endpoints

The project exposes the following API endpoints:
- GET <font color="aqua">/</font>: Retrieve all users.
- GET <font color="aqua">/:email</font>: GET by specific ID request: Retrieve a single user with email ID
- POST <font color="aqua">/</font>: Create a new user
- PUT <font color="aqua">/:email</font>: Update the details of a user by email ID
- DELETE <font color="aqua">/:email</font>: Delete a user by email ID
- POST <font color="aqua">/user/login</font>: login as a User.

## Technologies Used

- Node.js
- Express.js

## Contributing

Contributions are welcome! If you encounter any issues or have suggestions for improvements, please feel free to open an issue or submit a pull request.

