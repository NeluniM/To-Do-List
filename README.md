## Todo List Application ✅📝  

A full-stack **Todo List application** built using the **MERN stack** (MongoDB, Express.js, React.js, Node.js). This app helps users efficiently create, update, delete, and manage tasks.  

---  

## Features ✨  
- 🖥️ **Frontend (Client):** Interactive React-based user interface for managing tasks.  
- 🛠️ **Backend (Admin):** Node.js/Express server with CRUD operations powered by MongoDB.  
- 📱 **Responsive Design:** A smooth and user-friendly experience across devices.  

---  

## Technologies Used 🚀  
- **Frontend:** React, CSS 🎨  
- **Backend:** Node.js, Express.js, MongoDB, Mongoose 🗄️  
- **Other Tools:** npm, Vite (for development) 🛠️  

---  

## Project Structure 🗂️  
```  
/Server  
├── Models  
│   └── Todo.js           # Mongoose schema for tasks  
├── index.js              # Backend entry point  

/todolist /src  
├── App.jsx               # Main React component  
├── Home.jsx              # Task display page  
└── Create.jsx            # Task creation page  

/public  
├── index.html            # React's entry point HTML  
└── package.json          # React dependencies  
```  

---  

## How to Run the Application 🏃‍♂️💻  

### Prerequisites ⚙️  
1️⃣ **Node.js** and **npm** installed.  
2️⃣ **MongoDB** running locally or accessible via a connection string.  

### Steps to Run the Application 🔧  

#### Backend (Admin) 🛠️  
1️⃣ Navigate to the `Server` folder:  
   ```bash  
   cd Server  
   ```  

2️⃣ Install backend dependencies:  
   ```bash  
   npm install  
   ```  

3️⃣ Start the backend server:  
   ```bash  
   node index.js  
   ```  

4️⃣ The backend will run at `http://localhost:5000` (or the port configured in your `index.js`).  

---  

#### Frontend (Client) 🎨  
1️⃣ Navigate to the `todolist` folder:  
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

4️⃣ The frontend will be available at `http://localhost:3000`.  

---  

## Additional Information ℹ️  
- **Languages Used**: JavaScript, JSX, CSS 🌐  
- **Database**: MongoDB (using Mongoose for schema modeling) 🗄️  
- **Server**: Node.js with Express.js 🛠️  
- **Frontend Library**: React.js 🎨  

---  

