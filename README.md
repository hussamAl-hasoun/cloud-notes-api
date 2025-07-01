# 🗒️ Cloud Notes API

A lightweight, containerized **FastAPI** project for storing and managing personal notes.  
This project demonstrates your skills in **Python**, **FastAPI**, **Docker**, and **SQLite** — with clean, production-style structure.

---

## 🚀 Features

- Add, view, and delete notes using a RESTful API
- Built with FastAPI and Pydantic models
- Uses SQLite as a simple persistent database
- Swagger UI for easy testing: [http://localhost:8000/docs](http://localhost:8000/docs)
- Dockerized for consistent development & deployment

---

## 📁 Project Structure
fastapi-devops-project/
├── app/
│ ├── main.py # نقطة الدخول
│ ├── models.py # نماذج قاعدة بيانات SQLAlchemy
│ ├── schemas.py # مخططات Pydantic
│ └── database.py # اتصال قاعدة البيانات (SQLite)
├── Dockerfile
├── requirements.txt
└── README.md

