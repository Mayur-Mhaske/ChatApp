# ChatApp
Chat Web Application
Sure! Here's the content you can directly copy and paste into your README file:

---

# **Chat Application**

This is a full-stack **dynamic and responsive Chat Application** built with the MERN (MongoDB, Express.js, React.js, Node.js) stack. The application includes real-time messaging capabilities powered by **Socket.IO** and secure authentication using **JWT (JSON Web Token)**.

---

## **Features**
- Real-time messaging with Socket.IO.
- User authentication and authorization using JWT.
- Responsive and modern UI built with React.js and styled using Tailwind CSS.
- Backend API built with Express.js and Node.js.
- MongoDB as the database for efficient data storage and retrieval.

---

## **Technologies Used**

### **Main Stack**
| Technology      | Description                                  |
|-----------------|----------------------------------------------|
| **MongoDB**     | NoSQL database used for storing application data. |
| **Express.js**  | Backend framework for handling server-side operations. |
| **React.js**    | Frontend library for building dynamic and interactive user interfaces. |
| **Node.js**     | JavaScript runtime for server-side programming. |

### **Additional Tools and Libraries**
| Technology      | Description                                  |
|-----------------|----------------------------------------------|
| **Tailwind CSS**| Utility-first CSS framework for styling the UI. |
| **Socket.IO**   | Enables real-time, bidirectional communication between client and server. |
| **JWT**         | Provides secure token-based authentication. |

---

## **Installation and Setup**

### **Prerequisites**
- Node.js and npm installed on your system.
- MongoDB database setup and running locally or remotely.

### **Steps to Run the Application**
1. Clone the repository:
   ```bash
   git clone https://github.com/Mayur-Mhaske/ChatApp.git
   ```
2. Navigate to the project directory:
   ```bash
   cd ChatApp
   ```
3. Install dependencies for both the backend and frontend:
   ```bash
   # For backend
   cd backend
   npm install

   # For frontend
   cd ../frontend
   npm install
   ```
4. Configure environment variables:
   - Create a `.env` file in the `backend` folder with the following variables:
     ```env
     MONGO_URI=<your_mongo_db_connection_string>
     JWT_SECRET=<your_jwt_secret>
     ```
5. Start the application:
   ```bash
   # Backend
   cd backend
   npm start

   # Frontend
   cd ../frontend
   npm start
   ```

6. Open your browser and navigate to `http://localhost:3000` to see the application in action.

---

## **Project Structure**
```
ChatApp/
├── backend/        # Backend code (Node.js + Express.js)
├── frontend/       # Frontend code (React.js)
└── README.md       # Documentation
```

---

## **Contributing**
Contributions are welcome! Please fork the repository, make your changes, and submit a pull request.

---

