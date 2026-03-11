🏨 Hostel Management System

A web-based Hostel Management System developed to simplify hostel administration tasks such as student registration, room allocation, complaint management, and payment handling.

This project demonstrates backend development using Flask and Django frameworks, combined with a structured frontend built using HTML and CSS.

📌 Project Overview

Managing hostel operations manually can be inefficient and prone to errors.
This project provides a centralized digital platform that allows hostel administrators and students to manage hostel-related activities efficiently.

The system includes multiple backend implementations:

Flask-based application

Django-based application

API integration module

The project showcases different backend approaches while maintaining similar hostel management functionalities.

🚀 Features
👤 User Management

Student Signup and Login

User Profile Management

Ability to update personal information

🏢 Hostel Management

View hostel details

Room allocation system

Hostel dashboard for monitoring activities

🛠 Complaint & Maintenance System

Submit maintenance complaints

Track complaint status

💳 Payment System

Hostel fee payment page

Payment record management

⭐ Feedback System

Students can submit feedback regarding hostel services

📄 Additional Pages

About Page

Terms and Conditions

Dashboard Overview

🛠 Tech Stack
Backend

Python

Flask

Django

Frontend

HTML

CSS

Database

SQLite

Tools & Version Control

Git

GitHub

📂 Project Structure
hostel-management-system
│
├── CE-1 Flask
│   ├── templates
│   │   ├── about.html
│   │   ├── base.html
│   │   ├── complaint_and_maintenance.html
│   │   ├── dashboard.html
│   │   ├── feedback.html
│   │   ├── hostel_details.html
│   │   ├── login.html
│   │   ├── payment.html
│   │   ├── profile.html
│   │   ├── room_allocation.html
│   │   └── signup.html
│   │
│   ├── static
│   │   ├── css
│   │   └── images
│   │
│   ├── app.py
│   └── app.db
│
├── CE-2 Django
│   ├── Hostel
│   ├── Hostels
│   ├── app2
│   │   ├── models.py
│   │   ├── views.py
│   │   ├── forms.py
│   │   ├── urls.py
│   │   └── admin.py
│   │
│   ├── manage.py
│   └── db.sqlite3
│
└── CE-3 API
⚙️ Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/kashish-sachdeva-ds/hostel-management-system.git
cd hostel-management-system
2️⃣ Run the Flask Version
cd "CE-1 Flask"
python app.py

The Flask application will start on the local development server.

3️⃣ Run the Django Version
cd "CE-2 Django"
python manage.py runserver

Open your browser and visit:

http://127.0.0.1:8000/
🔮 Future Improvements

Role-based authentication (Admin / Student)

Integration with online payment gateways

Email notification system

Improved UI using modern frontend frameworks (React / Bootstrap)

Deployment on cloud platforms (AWS / Heroku / Vercel)

👥 Contributors

Kashish Sachdeva

Team Collaboration Project

📜 License

This project was developed for educational and learning purposes.
