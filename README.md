```markdown
# 📝 Django Blog Platform

A simple blog platform built with **Django** where users can register, log in, create posts, and leave comments.  
It also supports **media file uploads (images)** and includes Django’s built-in authentication system.

---

## 🚀 Features
- User registration and authentication (login/logout).
- Create, edit, and delete blog posts.
- Add comments to posts.
- Upload images to posts.
- Django admin panel to manage posts, comments, and users.
- Responsive templates using Django template system.

---

## 🛠️ Tech Stack
- **Backend:** Django (Python)
- **Database:** SQLite (default, can be changed to PostgreSQL/MySQL)
- **Frontend:** HTML, CSS (Django templates)
- **Authentication:** Django Auth
- **File Storage:** Django Media

---

## 📂 Project Structure
```

BlogProject/
│── blog/                # Blog app (posts & comments)
│── blog\_project/        # Project settings
│── templates/           # HTML templates
│── media/               # Uploaded images
│── static/              # Static files (css, js)
│── manage.py

````

---

## ⚙️ Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/django-blog-platform.git
   cd django-blog-platform
````

2. Create and activate a virtual environment:

   ```bash
   python -m venv venv
   source venv/bin/activate    # On Linux/Mac
   venv\Scripts\activate       # On Windows
   ```

3. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Apply migrations:

   ```bash
   python manage.py migrate
   ```

5. Create a superuser (admin account):

   ```bash
   python manage.py createsuperuser
   ```

6. Run the development server:

   ```bash
   python manage.py runserver
   ```

7. Open in browser:

   ```
   http://127.0.0.1:8000/
   ```

---

## 📸 Screenshots

(Add some screenshots here after running the project)

---

## 🔐 Authentication Pages

Thanks to Django’s `django.contrib.auth.urls`, the following routes are available:

* `/accounts/login/` – Login
* `/accounts/logout/` – Logout
* `/accounts/password_change/` – Change password
* `/accounts/password_reset/` – Reset password
* `/accounts/signup/` – User registration (custom view)

---

## 👨‍💻 Author

Developed by \[Your Name].
This project is part of my **portfolio**.

---

## 📜 License

This project is licensed under the MIT License.
