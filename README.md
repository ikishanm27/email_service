# 📧 Email Service API

A high-performance **Email Service REST API** built with **FastAPI** that enables users to register, authenticate, send and receive emails, and manage their inbox through secure, token-based authentication. The application follows RESTful principles and provides a scalable backend for email management.

## 🚀 Features

* 🔐 User Registration & Authentication
* 🔑 JWT-based Authentication
* 📧 Send emails to registered users
* 📥 Retrieve received emails (Inbox)
* 📤 View sent emails
* 🗑️ Delete emails
* 👤 User-specific email management
* ✅ Password hashing for secure credential storage
* ⚡ FastAPI automatic interactive API documentation
* 🛡️ Input validation using Pydantic models
* 🗄️ SQLite database with SQLAlchemy ORM

## 🛠️ Tech Stack

### Backend

* FastAPI
* Python
* SQLAlchemy
* Pydantic
* Uvicorn

### Database

* SQLite

### Authentication

* JWT (JSON Web Tokens)
* Password Hashing (Passlib/Bcrypt)

## 📂 Project Structure

```text
email_service/
│── app/
│   ├── api/
│   ├── models/
│   ├── schemas/
│   ├── database/
│   ├── services/
│   ├── utils/
│   ├── auth/
│   └── main.py
│
├── requirements.txt
├── README.md
└── .env
```

> *The structure above is an example. Adjust it if your project uses different folder names.*

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

**Linux/macOS**

```bash
python3 -m venv venv
source venv/bin/activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Configure environment variables

Create a `.env` file and add the required configuration.

Example:

```env
SECRET_KEY=your_secret_key
ALGORITHM=HS256
ACCESS_TOKEN_EXPIRE_MINUTES=30
DATABASE_URL=sqlite:///./email.db
```

### 5. Run the application

```bash
uvicorn app.main:app --reload
```

The API will be available at:

```
http://127.0.0.1:8000
```

## 📖 API Documentation

FastAPI automatically generates interactive API documentation.

* **Swagger UI**

  ```
  http://127.0.0.1:8000/docs
  ```

* **ReDoc**

  ```
  http://127.0.0.1:8000/redoc
  ```

## 📌 Main API Endpoints

| Method | Endpoint        | Description                        |
| ------ | --------------- | ---------------------------------- |
| POST   | `/register`     | Register a new user                |
| POST   | `/login`        | Authenticate user and generate JWT |
| POST   | `/emails/send`  | Send an email                      |
| GET    | `/emails/inbox` | View inbox                         |
| GET    | `/emails/sent`  | View sent emails                   |
| GET    | `/emails/{id}`  | Get email details                  |
| DELETE | `/emails/{id}`  | Delete an email                    |

> Update the endpoints above if your API uses different routes.

## 📸 Screenshots

Add screenshots of:

* Swagger UI (`/docs`)
* User Registration
* Login
* Send Email
* Inbox
* Sent Emails

## 🎯 Learning Outcomes

This project demonstrates:

* FastAPI framework
* REST API development
* JWT Authentication
* Password Hashing
* SQLAlchemy ORM
* SQLite database integration
* Pydantic validation
* Dependency Injection
* CRUD Operations
* API documentation with Swagger

## 🔮 Future Improvements

* Email attachments
* Search and filtering
* Pagination
* Email notifications
* Refresh tokens
* Role-based access control
* PostgreSQL support
* Docker deployment

## 📄 License

This project is licensed under the MIT License.

## 👨‍💻 Author

**Kishan**

GitHub: https://github.com/ikishanm27
