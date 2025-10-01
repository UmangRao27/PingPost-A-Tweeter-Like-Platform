# PingPost-A-Tweeter-Like-Platform
PingPost is a mini social media application built with Django where users can register, login, create, edit, and delete tweets (short posts) with optional photo uploads.

It’s a beginner-friendly project that demonstrates user authentication, CRUD operations, and Django templates in action.

## 🚀 Features

🔐 User Authentication – Register, login, and logout securely.

📝 Create Tweets – Post short text messages (up to 240 characters) with optional images.

✏️ Edit & Delete Tweets – Users can only modify or remove their own tweets.

🖼️ Photo Uploads – Attach images to posts (stored in /media/photos/).

📅 Timestamped Posts – Each tweet shows created & updated time.

👤 User-based Access – Only logged-in users can create/edit/delete posts; guests are redirected to login.

📱 Responsive UI – Styled with Bootstrap for a clean, mobile-friendly interface.

## 🛠️ Tech Stack

Backend: Django (Python)

Frontend: Django Templates + Bootstrap

Database: SQLite

Auth: Django built-in authentication system

Media Handling: Django ImageField for photo uploads
