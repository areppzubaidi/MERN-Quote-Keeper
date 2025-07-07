
# 🧠 MERN Quote Keeper

A beginner-friendly **MERN stack project** to save and view motivational quotes.  
This project helps you understand how to build a full-stack web app using:

- 🗂️ **MongoDB** (Database)
- ⚙️ **Express.js** (Backend Framework)
- 🌐 **React.js** (Frontend UI)
- 🖥️ **Node.js** (Runtime)

---

## ✅ Features

- 📝 Add new quotes (text + author)
- 📋 View all saved quotes
- 🔗 Full-stack integration (frontend ↔ backend ↔ database)
- 🔧 Built with only essential packages — perfect for learning

---

## 📁 Project Structure

```

mern-quote-keeper/
├── backend/
│   ├── server.js
│   └── models/Quote.js
├── frontend/
│   ├── public/
│   └── src/
│       ├── App.js
│       └── index.js
├── README.md

````

---

## 🔧 Prerequisites

Make sure the following are installed:

- [Node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/)
- [MongoDB](https://www.mongodb.com/try/download/community)
- Git (optional but recommended)

---

## 🚀 Getting Started

### 1. Start MongoDB Locally

```bash
mongod
#after: Starts MongoDB database server on port 27017
````

---

## 🖥️ Backend Setup (`backend/`)

### Step 1: Install dependencies

```bash
cd backend
#after: Move into the backend project folder

npm install express mongoose cors
#after: Installs Express (web framework), Mongoose (MongoDB connector), and CORS support
```

### Step 2: Create backend files

✅ `server.js`
(see full code in previous step)

### Step 3: Start the backend server

```bash
node server.js
#after: Launches your backend on http://localhost:5000
```

---

## 🌐 Frontend Setup (`frontend/`)

### Step 1: Create React App

```bash
cd ../
#after: Go back to the root directory

npx create-react-app frontend
#after: Scaffolds a new React project in the 'frontend' folder

cd frontend
#after: Enter the React frontend folder

npm install axios
#after: Installs Axios to make HTTP requests to the backend
```

### Step 2: Replace `src/App.js` with project code

✅ Paste in the React code
(see full App.js code in previous message)

### Step 3: Run the frontend server

```bash
npm start
#after: Starts React development server at http://localhost:3000
```

---

## 🧪 Example Flow

1. Open `http://localhost:3000` in your browser
2. Add a new quote
3. View it instantly from MongoDB
4. Data persists on refresh 🎉

---

## 🧠 What You'll Learn

* How React sends requests to a backend
* How Express handles and stores data
* How MongoDB saves documents with Mongoose
* Full CRUD basics

---

## 📚 Useful Commands Recap

```bash
# Start MongoDB
mongod
#after: Starts the MongoDB server

# Start backend
cd backend
node server.js
#after: Starts Express backend on port 5000

# Start frontend
cd ../frontend
npm start
#after: Runs React frontend on port 3000
```



