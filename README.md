# Django Blog Application

A simple blog app built using Python and Django, where users can create accounts, log in, and manage blog posts. Users can also view other users' posts and update their own profiles.

## Features
- **User Authentication**: Sign up, log in, and log out.
- **Profile Management**: Update email, username, password, and profile picture.
- **CRUD Operations for Posts**: Create, view, edit, and delete blog posts.
- **Responsive Design**: Accessible on both desktop and mobile devices.

## Getting Started

### Prerequisites
- Python 3.x
- [pip](https://pip.pypa.io/en/stable/installation/) (Python package installer)
- [virtualenv](https://virtualenv.pypa.io/en/latest/) (for creating isolated environments)

### Installation

1. **Clone the repository**
    ```bash
    git clone https://github.com/abdurazii/django-blog.git
    cd django-blog
    ```

2. **Create a virtual environment**
    ```bash
    python -m venv venv
    ```

3. **Activate the virtual environment**
   - On Windows:
     ```bash
     venv\Scripts\activate
     ```
   - On MacOS/Linux:
     ```bash
     source venv/bin/activate
     ```

4. **Install dependencies**
    ```bash
    pip install -r requirements.txt
    ```

5. **Database Migrations**
   Sometimes, migration files for the apps (`users` and `blog`) aren’t created automatically. Run migrations specifically for these apps:

    ```bash
    python manage.py makemigrations users
    python manage.py makemigrations blog
    ```

6. **Apply Migrations**
    ```bash
    python manage.py migrate
    ```

7. **Create a Superuser (optional)**
   To access the Django admin interface:
    ```bash
    python manage.py createsuperuser
    ```

8. **Run the Development Server**
    ```bash
    python manage.py runserver
    ```

## Usage
- Visit `http://127.0.0.1:8000` in your browser.
- Create an account, log in, and start creating, editing, and viewing blog posts!



---

**Note:** Remember to keep your `requirements.txt` updated if you add new dependencies.

Happy blogging!
