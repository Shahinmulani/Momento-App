# Momento

![Momento](c:\Users\Admin\Desktop\SnapShot\memories.PNG)

Memories - A Full Stack MERN Application
Introduction
This is a Full Stack MERN (MongoDB, Express, React, Node.js) Application called "Memories." It is a simple social media app that allows users to post and share interesting events from their lives. This project is designed to help you understand how the MERN stack works, providing a complete experience from backend to frontend development.

Features
User Authentication: Sign up and log in with secure user authentication.
CRUD Operations: Create, read, update, and delete posts.
Image Upload: Add images to your posts to share your memories visually.
Like Posts: Users can like posts to show appreciation.
Pagination: Display posts with pagination to handle large datasets efficiently.
Responsive Design: The app is fully responsive and works well on all screen sizes.
Technologies Used
Frontend: React, Redux, CSS
Backend: Node.js, Express
Database: MongoDB
Authentication: JWT (JSON Web Tokens)
Version Control: Git
Project Structure
client/: Contains the frontend React code.
server/: Contains the backend Node.js and Express code.
models/: MongoDB schemas and models for the app.
routes/: API routes for handling CRUD operations and user authentication.
controllers/: Functions to handle API requests and interact with the database.
Installation and Setup
Clone the repository:

bash
cd memories-app
Install dependencies:

For the server:

bash
Copy code
cd server
npm install
For the client:

bash
Copy code
cd client
npm install
Environment Variables:

Create a .env file in the server directory and add the following environment variables:

bash
Copy code
PORT=5000
MONGO_URI=your_mongo_database_uri
JWT_SECRET=your_secret_key
Run the Application:

To start the server:

bash
Copy code
cd server
npm start
To start the client:

bash
Copy code
cd client
npm start
Access the Application: Open your browser and navigate to http://localhost:3000 to see the app in action.

Contributing
Feel free to submit issues and pull requests if you want to contribute to this project. Any contributions are welcome!

License
This project is open-source and available under the MIT License.


Setup:
- run ```npm i && npm start``` for both client and server side to start the app
