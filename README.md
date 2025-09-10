### 📌 Small Blog Platform

**Technologies:** Django, Django ORM, SQLite, Bootstrap

#### 🚀 Features:

* 🔑 User registration and authentication (Django Auth)
* ✍️ Create, edit, and delete posts
* 💬 Comment on posts
* 🖼️ Upload media files (images)
* 📄 Simple and clean frontend (Bootstrap)
* ⚙️ Admin panel to manage users and posts

#### 🛠️ Installation:

```bash
# 1. Clone the repository
git clone https://github.com/username/blog-platform.git
cd blog-platform

# 2. Create virtual environment (pipenv or venv)
pipenv install --dev
pipenv shell

# 3. Run migrations
python manage.py migrate

# 4. Create superuser
python manage.py createsuperuser

# 5. Start development server
python manage.py runserver
```

#### 📂 Project Structure:

```
blog-platform/
├── manage.py
├── blog/           # Main app (posts and comments)
├── users/          # User management
├── media/          # Uploaded files
├── templates/      # HTML templates (Bootstrap)
└── static/         # CSS, JS, images
```

#### 🌟 Future Improvements:

* Like/Dislike system
* Categories and tags
* User profiles
