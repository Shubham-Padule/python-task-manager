# 🧩 Python Task Manager (Django)

A simple yet scalable Task Manager application built using Django, designed to manage tasks with user authentication and status tracking.  
Currently in **active development phase**.

## 🚀 Features
- User-based task management
- Create, update, delete tasks
- Task status (Pending / Completed)
- Secure authentication
- Clean and modular Django architecture

## 🛠 Tech Stack
- Backend: Django (Python)
- Database: SQLite (Dev) / PostgreSQL (Future)
- Version Control: Git & GitHub

## 📂 Project Status
🔧 Development Phase  
Upcoming:
- REST APIs
- Frontend integration
- Role-based access
- Deployment pipeline

## ⚙️ Setup Instructions
```bash
git clone https://github.com/USERNAME/python-task-manager.git
cd python-task-manager
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
