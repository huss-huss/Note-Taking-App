# Note-Taking-App
MERN Stack Project
This is a MERN (MongoDB, Express, React, Node.js) stack project. It includes a frontend client and a backend server. Follow the instructions below to set up and run the project.

Prerequisites
Node.js (version 16.13.0 recommended)
npm (Node Package Manager)
Installation
Clone the repository to your local machine.

Open a terminal and navigate to the root directory of the project.

Install dependencies for the backend server by running the following command:

Copy code
npm install
Navigate to the client directory:

bash
Copy code
cd client
Install dependencies for the frontend client by running the following command:

Copy code
npm install
Create a .env file in the root directory of the project and add the following content:

bash
Copy code
MONGO_URI=mongodb://localhost:27017/noteDB
TOKEN_SECRET=thisisafakejwtsecretkey
Replace the MONGO_URI value with your MongoDB connection string if needed. The provided TOKEN_SECRET is a placeholder and can be changed to a more secure value.

If your current Node.js version is not 16.13.0, you can use a version manager like nvm to switch to the recommended version:

perl
Copy code
nvm install 16.13.0
nvm use 16.13.0
Note: If you don't have nvm installed, please refer to the nvm documentation for installation instructions.

Running the Project
To run the project, execute the following command in the root folder:

arduino
Copy code
npm run dev
This command will concurrently start both the frontend client and the backend server.

The frontend client will be available at http://localhost:3000.
The backend server will be running at http://localhost:3001.
You can access the application by opening the provided URL in a web browser.

Switching back to your Node.js version
After you have finished running the project, you can switch back to your original Node.js version using nvm:

perl
Copy code
nvm use <your-node-version>
Replace <your-node-version> with the version you were using before.
