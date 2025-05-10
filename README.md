# 📚 iBook – MERN Stack Book Repository

A full-stack MERN (MongoDB, Express, React, Node.js) web application that allows users to browse, search, and filter books by genre and rating. Users can also add new books to the list. The application includes secure authentication using JSON Web Tokens (JWT) and is deployed on Heroku.

🔗 **Live Demo**: [iBook Web App](http://ibooksweb.herokuapp.com/books)

---

## 🚀 Features

- 🔐 JWT-based user authentication
- 🔎 Search functionality for books
- 🎯 Filter books by genre and rating
- ➕ Add new books to the collection
- 🧾 View list of available books
- 📱 Responsive design for mobile and desktop
- 🌐 Fully deployed on Heroku

---

## 🛠️ Tech Stack

**Frontend:**
- React
- React Router
- Axios
- Bootstrap or custom CSS

**Backend:**
- Node.js
- Express.js
- MongoDB (with Mongoose)
- JWT for authentication

**Deployment:**
- Heroku (Backend & Frontend combined)

---

## 📦 Installation & Setup (Local)

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/ibook.git
   cd ibook
   ```

2. **Install server dependencies**
   ```bash
   cd backend
   npm install
   ```

3. **Install client dependencies**
   ```bash
   cd ../frontend
   npm install
   ```

4. **Environment Variables**
   Create a `.env` file in the `backend/` directory with the following:
   ```
   PORT=5000
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret_key
   ```

5. **Run the app**
   ```bash
   # From project root
   cd backend
   npm run server  # starts backend on port 5000

   # In another terminal
   cd frontend
   npm start  # starts frontend on port 3000
   ```

---

## 📁 Folder Structure

```
ibook/
├── backend/
│   ├── models/
│   ├── routes/
│   ├── controllers/
│   └── server.js
├── frontend/
│   ├── src/
│   └── public/
├── README.md
```

---

## 🧑‍💻 Author

**Srija Dasgupta**  
🔗 [LinkedIn](https://linkedin.com/in/srijadasgupta)  
✉️ [mamandasgupta@gmail.com](mailto:mamandasgupta@gmail.com)

---


