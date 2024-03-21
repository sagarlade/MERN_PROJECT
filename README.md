#MERN STACK PROJECT

RESTAURANT RESERVATION is a web application built using the MERN (MongoDB, Express.js, React.js, Node.js) stack. It allows users to make reservations at a restaurant.


Development:
Babel (for ES6+ support)
Webpack (for bundling frontend assets)
Nodemon (for automatic server restarts during development)
ESLint and Prettier (for code linting and formatting)


Install dependencies for both frontend and backend:

cd frontend
npm install
cd ../backend
npm install


Set up environment variables:

Create a .env file in the backend directory.

Define the following variables:
PORT=3000
MONGODB_URI=your_mongodb_uri


Run:

cd backend
nodemon server.js


cd frontend
npm run dev
Open your browser and navigate to http://localhost:3000 to access the application.
