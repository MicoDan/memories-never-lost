Memories Never Lost Project
--------------------------------

The MERN Memories project is a full-stack web application that allows users to post and share their favorite memories. It is built using the MERN stack (MongoDB, Express, React, Node.js), which provides a robust and scalable foundation for developing modern web applications.

Features
-----------
Create and publish memories with titles, descriptions, and images.
Like and interact with other users' memories.
Real-time updates when new memories are posted or liked.
User authentication and authorization to secure private routes.
Responsive design for optimal viewing on various devices.

DEMO
-
https://memories-85fibgv7f-micodan.vercel.app


Technologies Used
----------------------
MongoDB: A NoSQL database used to store and manage memory data.
Express: A flexible and minimalistic web application framework for Node.js.
React: A popular JavaScript library for building user interfaces.
Node.js: A server-side JavaScript runtime environment.
Redux: A predictable state container for JavaScript apps.

Installation and Setup
-------------------------------
Clone this repository to your local machine using:
git clone https://github.com/MicoDan/memories-never-lost.git

Install the required dependencies for both the server and client:
----------------------------------------------------------------

Copy code
npm install
cd client
npm install
Create a .env file in the root of the project and provide the necessary environment variables:
-------------------------------------------------------

env

MONGODB_URI=your_mongodb_connection_string
PORT = your_port

Run the development server and client concurrently:
-
Copy code
npm run dev
Open your browser and access the application at http://localhost:3000.

Folder Structure
-
client: Contains the frontend code (React).
server: Contains the backend code (Node.js and Express).
public: Static assets and the HTML template for the React app.
Contributing
Contributions are always welcome! If you find any bugs or want to improve the project, feel free to open an issue or submit a pull request.

License
This project is licensed under the MIT License.




