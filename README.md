# Django Blog Practice

A simple Django-powered blog where an admin can create posts, and users can view and manage a "Read Later" list.

## Features
- Only the **admin** can create blog posts.
- The **latest three** posts are dynamically displayed on the main page.
- Users can view all posts.
- Users can **add** or **remove** posts from their **Read Later** list.

## Installation & Setup
### 1. Clone the repository
```sh
git clone https://github.com/SLEEPERSUNLESS/django-blog-practice.git
cd django-blog-practice
```

### 2. Create and activate a virtual environment (optional but recommended)
```sh
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate
```

### 3. Install dependencies
```sh
pip install -r requirements.txt
```

### 4. Apply database migrations
```sh
python manage.py migrate
```

### 5. Create a superuser (to access the admin panel)
```sh
python manage.py createsuperuser
```
Follow the prompts to set up an admin account.

### 6. Run the development server
```sh
python manage.py runserver
```

Visit `http://127.0.0.1:8000/` in your browser.

## Usage
- Log in as an **admin** (`/admin`) to create new blog posts.
- Visit the homepage to see the latest posts.
- Click on a post to view it in detail.
- Use the "Read Later" button to save posts for later reading.

## License
This project is for learning purposes. Feel free to modify and expand it!
