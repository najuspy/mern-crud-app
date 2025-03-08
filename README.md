# MERN CRUD Application

![MERN Stack](https://img.shields.io/badge/Stack-MERN-green)
![License](https://img.shields.io/badge/License-ISC-blue)

A full-stack web application built with the MERN stack (MongoDB, Express, React, Node.js) that demonstrates fundamental CRUD (Create, Read, Update, Delete) operations.

## 🌐 Live Demo

Check out the live application: [MERN CRUD App](https://mern-crud-app-y6g1.onrender.com/)

## ✨ Features

- **Create**: Add new products to the database
- **Read**: View all products in an organized layout
- **Update**: Edit existing product information
- **Delete**: Remove products from the database
- **Responsive Design**: Works seamlessly on desktop and mobile devices
- **Modern UI**: Clean and intuitive user interface

## 🛠️ Technologies Used

### Backend
- Node.js
- Express.js
- MongoDB with Mongoose
- RESTful API design

### Frontend
- React.js
- Zustand for state management
- Chakra-UI for styling

### Deployment
- Render for hosting

## 📋 Prerequisites

To run this project locally, you need to have the following installed:

- Node.js (v14+)
- npm or yarn
- MongoDB (local instance or Atlas connection)

## 🚀 Installation and Setup

1. Clone the repository
  git clone https://github.com/yourusername/mern-crud-app.git
  cd mern-crud-app

2. Install dependencies for backend and frontend
  npm install
  cd frontend
  npm install
  cd ..

3. Create a `.env` file in the root directory with the following variables
  NODE_ENV=development
  PORT=5000
  MONGO_URI=your_mongodb_connection_string

4. Start the development server
   npm run dev
   
5. The application should now be running at `http://localhost:5173` (frontend) and `http://localhost:5000` (backend)


## 🧑‍💻 API Endpoints

| Method | Endpoint            | Description                  |
|--------|---------------------|------------------------------|
| GET    | /api/products       | Get all products             |
| POST   | /api/products       | Create a new product         |
| PUT    | /api/products/:id   | Update a product by ID       |
| DELETE | /api/products/:id   | Delete a product by ID       |

## 📝 License

This project is licensed under the ISC License.

## 🙏 Acknowledgements

- [MongoDB](https://www.mongodb.com/)
- [Express.js](https://expressjs.com/)
- [React.js](https://reactjs.org/)
- [Node.js](https://nodejs.org/)
- [Render](https://render.com/) for hosting

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check [issues page](https://github.com/najuspy/mern-crud-app/issues).

## 📧 Contact

Your Name - [najuspy@gmail.com](mailto:najuspy@gmail.com)

Project Link: [https://github.com/najuspy/mern-crud-app](https://github.com/najuspy/mern-crud-app)
