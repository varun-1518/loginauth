# Authentication System with Express and MongoDB  

This repository contains a simple authentication system built using Express.js and MongoDB for user authentication.  

## Features  

- **User Signup**: Allows users to sign up with a unique username and password.  
- **User Login**: Enables users to log in using their credentials.  
- **Password Hashing**: Securely stores passwords using `bcryptjs` for hashing.  
- **JWT Authentication**: Implements JSON Web Tokens (JWT) for user session management.  

## Technologies Used  

- **Node.js**: JavaScript runtime environment.  
- **Express.js**: Web application framework for Node.js.  
- **MongoDB**: NoSQL database for storing user credentials.  
- **Mongoose**: Object Data Modeling (ODM) library for MongoDB and Node.js.  
- **bcryptjs**: Library for password hashing and comparison.  
- **jsonwebtoken (JWT)**: For token-based authentication.  

## Prerequisites  

Make sure you have the following installed:  

- **Node.js**: [Download Node.js](https://nodejs.org/)  
- **MongoDB**: [Install MongoDB](https://www.mongodb.com/try/download/community)  

## Configuration  

- **Port**: The server runs on port `2012` by default. You can modify this in the `index.js` file.  
- **JWT Secret**: Change the secret key used for JWT generation and verification in the `index.js` file.  

## Installation  

1. Clone this repository:  
   ```bash  
   git clone https://github.com/varun-1518/loginauth.git  
   ```  

2. Navigate to the project directory:  
   ```bash  
   cd loginauth  
   ```  

3. Install dependencies:  
   ```bash  
   npm install  
   ```  

4. Start the server:  
   ```bash  
   node index.js  
   ```  

5. Access the server at `http://localhost:2012`.  

## License  

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.  
