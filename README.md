# 📝 Blogs Using API

## 🌍 Overview
This project demonstrates a blog system using an **in-memory storage approach**. Instead of using a database, blogs are stored in an array on one server (running on port `4000`). The main server (running on port `3000`) fetches data from this API server and serves it to the frontend.

---

## ⚡ Features
✅ **Two-server architecture** - One server handles blog storage (`4000`), another fetches and serves (`3000`).  
✅ **In-memory storage** - Blogs are stored in an array, eliminating the need for a database.  
✅ **External API fetching** - The main server pulls blog data from the API server.  
✅ **Fast & lightweight** - No database overhead, ensuring quick responses.  
✅ **Minimal dependencies** - Clean and simple implementation.  

---

## 🏗️ Project Structure
```bash
Directory structure:
└── muke2110-blogs-using-api/
    ├── index.js
    ├── package.json
    ├── server.js
    ├── public/
    │   └── styles/
    │       └── main.css
    ├── views/
        ├── index.ejs
        └── modify.ejs

```

---

## 🚀 Getting Started

### 1️⃣ Prerequisites
- **Node.js & npm** installed. Get it [here](https://nodejs.org/).

### 2️⃣ Installation
Clone the repository and install dependencies:
```bash
git clone https://github.com/muke2110/Blogs-using-API.git
cd Blogs-using-API
npm install
```

### 3️⃣ Start the Servers
#### Start the API Server (port 4000):
```bash
node index.js
```
#### Start the Main Server (port 3000):
```bash
node server.js
```

### 4️⃣ Access the Application
📍 API Server: `http://localhost:4000/`
📍 Main Server: `http://localhost:3000/`
📍 Blog Frontend: `http://localhost:3000/`

---

## 🔍 How It Works
🔹 Users request blogs from `http://localhost:3000/`.  
🔹 The main server fetches data from `http://localhost:4000/`.  
🔹 The API server (port `4000`) responds with blog data stored in an array.  
🔹 The main server processes and serves this data to the frontend.  
🔹 The frontend displays the fetched blogs to the user.  

---

## 📚 Learn More
📌 [Node.js Documentation](https://nodejs.org/en/docs/)  
📌 [Express.js Guide](https://expressjs.com/)  

---

## 🤝 Contributing
🎯 Fork the repository.  
🎯 Create a new branch: `git checkout -b feature-branch-name`  
🎯 Commit changes: `git commit -m "Added a cool feature"`  
🎯 Push changes: `git push origin feature-branch-name`  
🎯 Open a Pull Request! 🚀  

---

## 📜 License
This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

---

## 📞 Contact
For any queries or suggestions, feel free to reach out!  
📧 Email: mukesh.nagineni@gmail.com  
📱 Phone: +91 91003 80866  
🌐 GitHub: [muke2110](https://github.com/muke2110)

---

✨ **Simple yet efficient blog management using in-memory storage!** 🚀

