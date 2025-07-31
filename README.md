# 📝 Django Blog Site Project

A fully functional blog web application built with Django. This project demonstrates user authentication, CRUD operations, template management, and dynamic content rendering. Ideal for learning how to integrate databases, handle forms, and manage user-generated content in Django.

---

## 🎯 Objective

Build a blog platform where users can:

- Create, read, update, and delete posts.
- Register and log in securely.
- Browse, search, and comment on posts.
- Manage blog content through the admin panel.

---

## 🔑 Key Features

### 1. 🔐 User Authentication
- User registration, login, and logout.
- Django’s built-in authentication system.

### 2. 📝 Blog Post Management (CRUD)
- **Create**: Add new blog posts with Django Model Forms.
- **Read**: Display all blog posts on the homepage with pagination.
- **Update**: Edit user-owned blog posts.
- **Delete**: Delete user-owned blog posts.

### 3. 🏷️ Categories & Tags
- Categorize posts using predefined `Category` model.
- Add flexible tags using `ManyToManyField`.

### 4. 💬 Comment System
- Allow authenticated users to post comments.
- Display all comments under the associated blog post.

### 5. 🔍 Search & Pagination
- Search blog posts by title or content.
- Paginate blog post listings for cleaner navigation.

### 6. 🎨 Template & Styling
- Base template with reusable navigation and footer.
- Styled using **Bootstrap** or custom CSS.
- Template inheritance via `base.html`.

### 7. ⚙️ Admin Panel Customization
- Admin access for blog management.
- All models registered in Django Admin.
- Superuser can add/edit/delete content easily.

---

## 🛠 Tools & Technologies

| Layer       | Tools Used                      |
|-------------|----------------------------------|
| Frontend    | HTML, CSS, Bootstrap             |
| Backend     | Django (Views, Models, Templates)|
| Database    | SQLite (default Django DB)       |

---

## 🚀 Getting Started

```bash
# 1. Clone the repository
git clone https://github.com/your-username/django-blog-site.git
cd django-blog-site

# 2. Create and activate a virtual environment
python -m venv venv
venv\Scripts\Activate.ps1   # On Windows PowerShell

# 3. Install dependencies
pip install -r requirements.txt

# 4. Apply database migrations
python manage.py makemigrations
python manage.py migrate

# 5. Create a superuser
python manage.py createsuperuser

# 6. Run the development server
python manage.py runserver

# Visit the site
# http://127.0.0.1:8000/
```

<pre> ```plaintext myblog/ │ ├── blog/ # Blog app (posts, views, models) ├── users/ # User registration and profiles ├── templates/ # HTML templates ├── static/ # Static files (CSS, JS) ├── media/ # Uploaded images/files ├── manage.py # Django project entry point └── requirements.txt # Project dependencies ``` </pre>
