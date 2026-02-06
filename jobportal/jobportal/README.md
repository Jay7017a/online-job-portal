💼 Online Job Portal for Freshers – Django Project

📌 Project Overview

The Online Job Portal is a web-based application developed for freshers to search and apply for jobs easily.
It allows companies/admins to post job openings and students/users to register, login, and apply for jobs.

---

🚀 Features

- 👤 User Registration & Login Authentication
- 🧑‍💼 Job Posting by Admin/HR
- 📄 View Available Jobs
- ✅ Apply for Jobs
- 🔒 Secure Session Management
- 🗄️ MySQL Database Integration
- 🛠️ Django Admin Panel

---

🧰 Tech Stack

- Frontend: HTML, CSS
- Backend: Python, Django
- Database: MySQL
- Version Control: Git & GitHub

---

📁 Project Structure

jobportal/
│
├── accounts/        # Login & Registration
├── jobs/            # Job Module
├── templates/       # HTML Pages
├── manage.py
└── settings.py

---

⚙️ Installation & Setup

1️⃣ Clone the repository

git clone https://github.com/your-username/online-job-portal-django.git

2️⃣ Navigate to project folder

cd online-job-portal-django

3️⃣ Create virtual environment

python -m venv venv
venv\Scripts\activate

4️⃣ Install dependencies

pip install django mysqlclient

5️⃣ Configure MySQL in "settings.py"

6️⃣ Run migrations

python manage.py makemigrations
python manage.py migrate

7️⃣ Start server

python manage.py runserver

---

🌐 Application URLs

- Home → http://127.0.0.1:8000/
- Register → /register/
- Login → /login/
- Admin → /admin/

---

📊 Database Design

- User (Django default auth)
- Job
- Application

---

🎯 Use Case

- Freshers can search jobs
- Companies can post openings
- Easy job application tracking

---

🔮 Future Enhancements

- Resume Upload
- Company Dashboard
- Email Notifications
- Job Search Filters
- Deployment on Cloud

---

👩‍💻 Author

Banda Jaya Sree
B.Tech CSE – 3rd Year
KITS Markapur

📧 jayasreebanda510@gmail.com
🔗 GitHub: https://github.com/Jay7017a

---

⭐ If you like this project

Give it a ⭐ on GitHub!