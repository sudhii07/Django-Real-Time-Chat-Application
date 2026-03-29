# 💬 Django Real-Time Chat Application

## 🚀 Overview

This project is a **real-time chat application** built using **Django and Django Channels**, enabling users to communicate instantly through WebSockets. The application supports user authentication, friend management, and private messaging in a dynamic and interactive interface.

---

## ✨ Features

* 🔐 User Authentication (Login / Signup / Logout)
* 👥 Friend System (Add / Manage Friends)
* 💬 Real-Time Chat using WebSockets
* 📡 Django Channels Integration
* 🖼️ Profile Image Upload Support
* 📁 Organized Apps Structure (Accounts, Chats, Friends)
* ⚡ Fast and Responsive UI

---

## 🛠️ Tech Stack

* **Frontend:** HTML, CSS, JavaScript
* **Backend:** Django (Python)
* **Real-Time Communication:** Django Channels
* **ASGI Server:** Daphne
* **Database:** SQLite
* **Image Handling:** Pillow

---

## 📂 Project Structure

```
chat-application/
│── accounts/        # User authentication & profiles
│── chats/           # Chat functionality
│── friends/         # Friend management
│── static/          # CSS, JS files
│── templates/       # HTML templates
│── db.sqlite3       # Database
│── manage.py
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```
git clone https://github.com/your-username/chat-application.git
cd chat-application
```

### 2️⃣ Create Virtual Environment

```
python -m venv venv
venv\Scripts\activate   # Windows
```

### 3️⃣ Install Dependencies

```
pip install -r requirements.txt
```

### 4️⃣ Apply Migrations

```
python manage.py migrate
```

### 5️⃣ Run Server

```
python manage.py runserver
```

---

## 🌐 Usage

* Open browser: `http://127.0.0.1:8000/`
* Register a new account
* Add friends
* Start real-time chatting instantly

---

## 🔥 Future Enhancements

* ✅ Group Chat Feature
* ✅ Online/Offline Status
* ✅ Message Notifications
* ✅ Media Sharing (Images, Files)
* ✅ Deployment with Redis & Docker

---

## 📸 Screenshots

(Add your project screenshots here)

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork this repository and submit pull requests.

---

## 📄 License

This project is open-source and available under the MIT License.

---

## 👨‍💻 Author

Sudhan Angadi
GitHub: https://github.com/sudhii07

---

⭐ If you like this project, give it a star!
