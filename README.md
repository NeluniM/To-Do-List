# 📝 Todo List Application  

A full-stack **Todo List app** created with the **MERN stack** (MongoDB, Express.js, React.js, Node.js). This app allows users to easily manage tasks with a sleek, user-friendly interface for creating, updating, and deleting tasks.  

---

## ✨ Key Features  

- **Dynamic Frontend**: Built with React.js, offering real-time task updates.  
- **Powerful Backend**: Node.js and Express.js handle CRUD operations seamlessly.  
- **Secure Database**: MongoDB ensures task data is safely stored.  
- **Responsive Design**: Fully optimized for all screen sizes, from desktop to mobile.  
- **Real-Time Experience**: Changes reflect instantly across the UI.  

---

## 🛠️ Technologies  

- **Frontend**: React.js, CSS  
- **Backend**: Node.js, Express.js, MongoDB, Mongoose  
- **Development Tools**: npm, Vite  

---

## 🔍 Folder Structure  

```plaintext
/Server  
├── Models  
│   └── Todo.js       # Schema definition for tasks  
├── index.js          # Entry point for the backend  

/todolist /src  
├── App.jsx           # Main React component  
├── Home.jsx          # Task display page  
└── Create.jsx        # Task creation page  

/public  
├── index.html        # Root HTML file for the React app  
└── package.json      # Dependencies and scripts  
```  

---

## 🚀 How to Set Up and Run  

### Prerequisites  

1️⃣ Install **Node.js** and **npm**.  
2️⃣ Ensure **MongoDB** is running locally or via a remote connection string.  

---

### 1. Run the Backend  

1️⃣ Navigate to the `Server` folder:  
```bash  
cd Server  
```  

2️⃣ Install backend dependencies:  
```bash  
npm install  
```  

3️⃣ Start the server:  
```bash  
node index.js  
```  

4️⃣ Backend is available at `http://localhost:5000` or the configured port.  

---

### 2. Run the Frontend  

1️⃣ Go to the `todolist` folder:  
```bash  
cd todolist  
```  

2️⃣ Install frontend dependencies:  
```bash  
npm install  
```  

3️⃣ Start the React app:  
```bash  
npm start  
```  

4️⃣ Open `http://localhost:3000` to access the app.  

---

## 🔧 Future Improvements  

- **User Authentication**: Personalized task lists and secure logins.  
- **Reminders**: Notify users about due or upcoming tasks.  
- **Analytics Dashboard**: Track completion trends and task insights.  
- **Dark Mode**: Toggle between light and dark themes for better usability.  

---

## 📚 Additional Details  

- **Languages**: JavaScript, JSX, CSS  
- **Database**: MongoDB with Mongoose for schema management  
- **Frontend Framework**: React.js  
- **Backend**: Node.js and Express.js  

---
