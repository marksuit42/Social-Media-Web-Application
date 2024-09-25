## Frontend

1. Navigate to web folder and install dependencies

   ```sh
   cd frontend/frontend
   npm i
   ```

2. Start the react app

   ```sh
   npm start
   ```

## Backend

1. Navigate to web folder and install dependencies

   ```sh
   cd backend
   npm i
   ```

2. Add .env in the root directory. Here's an example env file for you.

   ```sh
   PORT=5000
   MONGO_URI= add you mangodb url
   JWT_SECRET=your_jwt_secret_key 
   ```

2. Start the backend server

   ```sh
   npm start
   ```

### To add seed data to the database
1. Navigate to server folder and run file seed.js<br>
  
   ```sh
   cd backend
   node seed.js
   ```
