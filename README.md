#Movie Booking API

A simple movie booking backend built with Node.js, Express, MongoDB, and JWT authentication. Users can sign up, log in, book movie tickets, and cancel bookings. Admins can add new movies.

#Features

User authentication (Sign up, Log in)
Admin-only movie creation with image upload
User movie booking and cancellation
JWT-based route protection
MongoDB as the database

##How to Run Locally
1. Clone the repository
git clone https://github.com/vaibhavkumar-06/webd-modules.git
cd webd-modules

3. Install dependencies
npm install express mongoose dotenv bcryptjs jsonwebtoken multer cors

5. Create .env file
In the root folder, create a file named .env:

PORT=5000
MONGO_URI=your_mongodb_uri_here
JWT_SECRET=your_secret_key_here
🔐 Replace your_mongodb_uri_here with your MongoDB Atlas URI and secret key of your choice.

4. Run the server
node server.js

📦 Technologies Used
Node.js
Express.js
MongoDB + Mongoose
JWT (jsonwebtoken)
bcryptjs
multer (for file uploads)
dotenv
cors
