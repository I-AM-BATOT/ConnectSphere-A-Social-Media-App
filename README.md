# 🌐 ConnectSphere – Mini Social Media Platform

## 📌 Project Description

ConnectSphere is a full-stack mini social media web application built using Node.js (Express.js) and MySQL. It allows users to connect with others by creating posts, liking, commenting, and following profiles. The application features a responsive design that works seamlessly across desktop, tablet, and mobile devices.

---

## 🚀 Features

### 🔐 User Authentication & Profiles

* User registration and login system
* Password hashing using bcrypt
* JWT/session-based authentication
* User profiles with:

  * Username
  * Email
  * Bio
  * Profile picture (optional)
* View other users' profiles

---

### 📝 Posts System

* Create, edit, and delete posts
* Each post includes text content and timestamp
* Displays posts in a feed (latest first)

---

### 💬 Comments System

* Add comments on posts
* Each comment includes user, text, and timestamp
* View comments under each post

---

### ❤️ Like System

* Like and unlike posts
* Display total likes count per post

---

### 👥 Follow System

* Follow/unfollow users
* View follower and following counts
* Option to view posts from followed users

---

## 🛠️ Tech Stack

* **Frontend:** HTML, CSS, JavaScript
* **Backend:** Node.js with Express.js
* **Database:** MySQL (XAMPP)
* **Authentication:** JWT / Sessions
* **Other Tools:** bcrypt, dotenv

---

## 📱 Responsive Design

The application is fully responsive and optimized for:

* 📱 Mobile devices
* 📲 Tablets
* 💻 Desktop screens

---

## ⚙️ Installation & Setup

```bash
# Clone the repository
git clone https://github.com/your-username/ConnectSphere.git

# Navigate into the project folder
cd ConnectSphere

# Install dependencies
npm install

# Start the server
npm start
```

---

## 🔑 Environment Variables

Create a `.env` file in the root directory:

```
PORT=5000
DB_HOST=localhost
DB_USER=root
DB_PASSWORD=yourpassword
DB_NAME=connectsphere
JWT_SECRET=your_secret_key
```

---

## 🗄️ Database Setup

1. Open XAMPP and start Apache & MySQL
2. Go to phpMyAdmin
3. Create a new database: `connectsphere`
4. Import the provided `database.sql` file

---

## 📂 Project Structure

```
ConnectSphere/
│── backend/
│── frontend/
│── database/
│── screenshots/
│── .gitignore
│── README.md
```

---

## 📸 Screenshots

<img width="1920" height="834" alt="Screenshot (228)" src="https://github.com/user-attachments/assets/9f27116c-bda8-4b10-997a-9cc53793d9c5" />
<img width="1920" height="851" alt="Screenshot (229)" src="https://github.com/user-attachments/assets/8b6e399e-4c48-47e7-8a36-fffa3cb2821b" />
<img width="1920" height="880" alt="Screenshot (230)" src="https://github.com/user-attachments/assets/9f1f6c3d-fc40-4e77-9313-bf9594e2b418" />
<img width="1920" height="869" alt="Screenshot (231)" src="https://github.com/user-attachments/assets/e9f3b00b-ceea-4de6-95c1-8677b4ce6257" />
<img width="593" height="808" alt="Screenshot (232)" src="https://github.com/user-attachments/assets/8915880c-7b06-4782-9b72-700a21cf953f" />



---



---

## 👨‍💻 Author

Your Name
GitHub: https://github.com/I-AM-BATOT


