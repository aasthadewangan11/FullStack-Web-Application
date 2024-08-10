# FullStack-Web-Application

## Development Environment Setup

To set up the development environment, follow these steps:

### Install Node.js and npm: 
Download and install Node.js from the official website: https://nodejs.org/en/download/


### Install MongoDB:
Download and install MongoDB from the official website: https://www.mongodb.com/download-center/community


### Clone the repository:
Clone the repository using Git: git clone https://github.com/your-username/assessment-management-system.git
Install dependencies: Run npm install in the root directory of the project to install the dependencies.
Create a MongoDB database: Create a new MongoDB database and update the MONGODB_URI environment variable in the .env file.

## Running the Application

To run the application, follow these steps:
Start the MongoDB server: Start the MongoDB server by running mongod in a separate terminal window.
Start the backend API: Run npm run start:backend in the root directory of the project to start the backend API.
Start the frontend application: Run npm run start:frontend in the root directory of the project to start the frontend application.
Access the application: Open a web browser and navigate to http://localhost:4200 to access the application.

## Testing the Application

To test the application, follow these steps:
Run unit tests: Run npm run test:unit in the root directory of the project to run the unit tests.
Run integration tests: Run npm run test:integration in the root directory of the project to run the integration tests.
Run end-to-end tests: Run npm run test:e2e in the root directory of the project to run the end-to-end tests.

## Environment Variables

The following environment variables are required:
MONGODB_URI: The URI of the MongoDB database.
JWT_SECRET: The secret key for JSON Web Tokens.
PORT: The port number for the backend API.
