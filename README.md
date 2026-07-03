# Online Examination Portal

An Online Examination Portal built using **Python**, **Django**, **HTML**, **CSS**, **JavaScript**, and **SQLite/MySQL**. The application enables administrators to create and manage exams while allowing students to take tests online and view their results instantly.

---

## Features

### Admin
- Secure admin login
- Manage students and faculty
- Create, update, and delete exams
- Add and manage questions
- Assign marks for each question
- View student performance
- Generate examination reports

### Student
- User registration and login
- View available examinations
- Attend online exams
- Automatic score calculation
- View exam history
- Download/View results

---

## Technologies Used

- Python
- Django
- HTML5
- CSS3
- Bootstrap
- JavaScript
- SQLite / MySQL

---

## Project Structure

```
OnlineExamPortal/
│── exam/
│── student/
│── teacher/
│── templates/
│── static/
│── media/
│── db.sqlite3
│── manage.py
└── requirements.txt
```

---

## Installation

### Clone the repository

```bash
git clone https://github.com/your-username/online-exam-portal.git
cd online-exam-portal
```

### Create a virtual environment

```bash
python -m venv venv
```

### Activate the environment

#### Windows

```bash
venv\Scripts\activate
```

#### Linux / macOS

```bash
source venv/bin/activate
```

### Install dependencies

```bash
pip install -r requirements.txt
```

### Apply migrations

```bash
python manage.py makemigrations
python manage.py migrate
```

### Create Superuser

```bash
python manage.py createsuperuser
```

### Run the server

```bash
python manage.py runserver
```

Open your browser and visit:

```
http://127.0.0.1:8000/
```

Admin Panel:

```
http://127.0.0.1:8000/admin/
```

---

## Modules

- Authentication
- Student Management
- Faculty Management
- Examination Management
- Question Management
- Result Management
- Dashboard

---

## Database

- SQLite (Default)
- MySQL (Optional)

---

## Future Enhancements

- Email Notifications
- Online Proctoring
- Certificate Generation
- PDF Result Download
- Timer-Based Examinations
- Leaderboard
- Analytics Dashboard

---

## Screenshots

- Home Page
- Student Dashboard
- Admin Dashboard
- Exam Page
- Result Page

(Add screenshots in the `screenshots/` folder.)

---

## Requirements

```
Python 3.10+
Django 4.x
Bootstrap 5
SQLite/MySQL
```

---

## License

This project is developed for educational and academic purposes.

---

## Author

Doddy Shashi Vardhan

GitHub: https://github.com/Shashi8931
