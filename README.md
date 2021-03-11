# API with JWT Authentication

## ✨ Features

- Register
- Login
- Authentication and Validation of Users 
- Private Routing

## 💻 Technologies used
- nodejs
- express
- @hapi/joi
- bcryptjs
- dotenv
- jsonwebtoken
- mongoose
- mongoDB atlas

## 🏠 To run it on localhost 
- create a cluster in mongoDB atlas
- create a .env file and add the db connection url given in mongoDB atlas as a variable (DB_CONNECT)
- add a random string in a variable called TOKEN_SECRET in the .env file
- run the command "npm install" on the terminal
- run this "nodemon index.js" on the terminal
- once the server is started and db is connected, make api calls in postman to get outputs (Example: http://localhost:3000/api/user/register)
