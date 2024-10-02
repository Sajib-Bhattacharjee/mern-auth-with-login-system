<div align="center">

# `🌟MERN Authentication Project🌟` 

</div>

      
A simple MERN stack project using the MVC architecture where users can register and log in. The project uses MongoDB Compass URL for the database connection. Upon successful login, users are greeted with a personalized message.
    
## `Project Structure`

```node

mern-auth/
│
├── backend/
│   ├── controllers/
│   │   └── userController.js
│   ├── models/
│   │   └── userModel.js
│   ├── routes/
│   │   └── userRoutes.js
│   ├── .env
│   ├── server.js
│   └── package.json
│
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   │   └── Login.js
│   │   │   └── Register.js
│   │   ├── App.js
│   │   ├── index.js
│   ├── package.json
│
├── README.md
└── .gitignore

```
  
## `Backend Setup`

1. Initialize the backend:

    ```bash
    mkdir mern-auth
    cd mern-auth
    mkdir backend
    cd backend
    npm init -y
    npm install express mongoose bcryptjs jsonwebtoken dotenv cors
    npm install nodemon --save-dev
    ```

2. Create the `server.js` file and set up the server.
3. Set up the `.env` file for MongoDB and JWT secret.
4. Create the `userModel.js` for user schema.
5. Create the `userController.js` for handling registration and login.
6. Define the `userRoutes.js` for API routes.
7. Add the following to `package.json` for nodemon:

    ```json
    "scripts": {
      "start": "node server.js",
      "server": "nodemon server.js"
    }
    ```

## `Frontend Setup`

1. Initialize the frontend using:

    ```bash
    cd ..
    npx create-react-app frontend
    cd frontend
    npm install axios react-router-dom
    ```

2. Create `Register.js` and `Login.js` components for user authentication.
3. Update `App.js` to set up routing for the registration and login pages.
4. Create a `styles.css` file for styling.

## `Styling`

Use `styles.css` to style the Register and Login pages. Ensure the CSS file is imported into `App.js` for consistent styling across the app.

## `Running the Project`

1. **Backend**:

    Run the backend server:

    ```bash
    cd backend
    npm run server
    ```

2.  **Frontend**: 

    Run the frontend app:

    ```bash
    cd frontend
    npm start
    ```

## `Technologies Used`

- **Frontend**: React, Axios, React Router DOM
- **Backend**: Node.js, Express, Mongoose, bcryptjs, jsonwebtoken, dotenv
- **Database**: MongoDB (using MongoDB Compass URL)

---
<div align="center">

##### 🛡️ `All rights reserved by Sajib Bhattacharjee @2024`

### 👨‍💻 `Created By-->`

**&copy; `Sajib Bhattacharjee`**

**💖 Dedicated to "Zahan" 💖**

> > > > ### 🙏 Thanks a Lot for Visiting...!!!

</div>
