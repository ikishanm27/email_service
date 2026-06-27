# 📧 Email Service Application

A full-stack email service application built with **Django** that allows users to securely register, log in, send and receive emails, and manage their inbox through a clean and responsive web interface.

## 🚀 Features

* 🔐 Secure User Authentication (Registration, Login & Logout)
* 📩 Send emails to registered users
* 📥 Receive and view incoming emails
* 📤 Sent Mail management
* 🗑️ Delete emails
* 👤 User-specific inbox and sent items
* 📱 Responsive user interface
* 🏗️ Built using Django's MVT (Model-View-Template) architecture

## 🛠️ Tech Stack

**Backend**

* Django
* Python

**Database**

* SQLite

**Frontend**

* HTML5
* CSS3
* JavaScript

## 📂 Project Structure

```
email_service/
│── email_service/      # Project settings
│── mail/               # Main application
│── templates/          # HTML templates
│── static/             # CSS, JavaScript, Images
│── db.sqlite3          # SQLite database
│── manage.py
└── README.md
```

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/ikishanm27/email_service.git
cd email_service
```

### 2. Create a virtual environment

**Windows**

```bash
python -m venv venv
venv\Scripts\activate
```

**Linux / macOS**

```bash
python3 -m venv venv
source venv/bin/activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Apply migrations

```bash
python manage.py migrate
```

### 5. Create a superuser (Optional)

```bash
python manage.py createsuperuser
```

### 6. Run the development server

```bash
python manage.py runserver
```

Open your browser and visit:

```
http://127.0.0.1:8000/
```

## 📸 Screenshots

Add screenshots of:

* Home Page
* Login Page
* Registration Page
* Inbox
* Compose Email
* Sent Emails
* Email Details

## 🎯 Learning Outcomes

This project demonstrates:

* Django MVT Architecture
* Authentication & Authorization
* CRUD Operations
* Database Management with SQLite
* Form Handling & Validation
* Template Rendering
* Static File Management
* Responsive Web Design

## 🔮 Future Improvements

* Email search functionality
* Rich text editor
* Attachments support
* Email notifications
* Pagination
* Password reset via email
* Dark mode
* REST API integration

## 🤝 Contributing

Contributions are welcome! Feel free to fork the repository, create a feature branch, and submit a pull request.

## 📄 License

This project is licensed under the MIT License.

## 👨‍💻 Author

**Kishan**

GitHub: https://github.com/ikishanm27
