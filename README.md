#  Connectly API

A simple social media backend built with Django REST Framework.  
Supports core features like users, posts, followers, likes, and comments.

---

##  Features

-  User Management
-  Posts (Create & View)
-  Likes
-  Comments
-  Follow System

---

##  Tech Stack

- Python
- Django
- Django REST Framework

---

##  Installation

```bash
# Clone repo
git clone https://github.com/yourusername/connectly-api.git

cd connectly-api

# Create virtual environment
python -m venv venv
venv\Scripts\activate   # Windows

# Install dependencies
pip install -r requirements.txt

# Run migrations
python manage.py makemigrations
python manage.py migrate

# Start server
python manage.py runserver
