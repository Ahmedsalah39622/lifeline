 LIFELINE 🚑 – Emergency Medical Services Platform

LIFELINE is a full-stack emergency response management system that helps streamline communication between patients and medical service providers. Built using Laravel and MySQL, it offers real-time service request handling, secure user roles, notifications, and a responsive admin dashboard.

> 📌 This project demonstrates back-end and system design capabilities, API architecture, role-based access control, and Docker-based environment management.



 🌐 Live Demo

> (Optional: add a link to live version or YouTube demo video if available)



 🧰 Tech Stack

| Layer         | Tech / Tool                         |
||-|
| Backend       | Laravel 10 (PHP)                    |
| Frontend      | Blade Templates + Bootstrap         |
| Database      | MySQL                               |
| Authentication| Laravel Breeze / Sanctum            |
| DevOps        | Docker + Docker Compose             |
| Notifications | Laravel Mail + System Alerts        |
| Testing       | PHPUnit                             |
| API           | RESTful API with token auth         |



 ⚙️ Features

- ✅ Role-based Access – Admin, Patient, Medical Provider
- 🏥 Emergency Reporting – Real-time patient request submission
- 🧑‍⚕️ Service Provider Panel – View & manage assigned cases
- 📊 Admin Dashboard – Centralized management & user controls
- 📬 Email & In-App Notifications – Case status updates
- 🔐 Secure Auth System – Login, register, forgot password
- 🛠️ Dockerized Environment – Easy setup & deployment
- 📡 RESTful APIs – Ready for integration with mobile or frontend apps



🖼️ Screenshots
![image](https://github.com/user-attachments/assets/b14e6927-7704-4f3d-ae41-99a6dc7935d3)

🚀 Getting Started

 Clone & Setup

git clone https://github.com/Ahmedsalah39622/lifeline.git
cd lifeline

composer install
cp .env.example .env
php artisan key:generate

 Set up your .env with DB credentials
php artisan migrate --seed
php artisan serve

Docker Setup
docker-compose up -d

Method	Endpoint	Description

POST	/api/login	Authenticate user
GET	/api/emergencies	Get all emergencies
POST	/api/emergencies	Submit new emergency
GET	/api/user/profile	Retrieve profile info

Full API documentation available in /routes/api.php

✅ Running Tests
php artisan test

📂 Folder Structure Highlights
├── app/
│   ├── Models/
│   ├── Http/Controllers/
│   └── Notifications/
├── routes/
│   ├── web.php
│   └── api.php
├── docker-compose.yml
├── resources/views/
├── tests/
└── .env.example

🎯 Future Enhancements

Real-time updates using WebSockets (Pusher or Laravel Echo)

Interactive maps to locate nearby service providers

Mobile app integration (Flutter/React Native)

Admin analytics dashboard with charts


👤 Author
Ahmed Mahmoud Salah Eldein Hassan Mohsen
https://github.com/Ahmedsalah39622/
https://www.linkedin.com/in/ahmed-mahmoud-salah-3727a034a/

