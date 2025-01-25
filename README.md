# Expense-Tracker-Django


A simple and efficient Expense Tracker web application built with **Django** and **PostgreSQL**. This project allows users to track their expenses, categorize them, and view detailed reports. 

## 🛠️ Tech Stack

- **Backend**: Django (Python)
- **Database**: PostgreSQL
- **Frontend**: HTML, CSS

## 🚀 Features

- User authentication (login and registration)
- Add, edit, and delete expenses
- View expenses by categories
- View expense summaries and reports
- Responsive design for desktop and mobile

## 🧑‍💻 Installation

1. Clone this repository:
    ```bash
    git clone https://github.com/yourusername/expense-tracker.git
    ```

2. Navigate to the project directory:
    ```bash
    cd expense-tracker
    ```

3. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

4. Set up PostgreSQL and create a new database.

5. Update your database configuration in `settings.py`:
    ```python
    DATABASES = {
        'default': {
            'ENGINE': 'django.db.backends.postgresql',
            'NAME': 'your_database_name',
            'USER': 'your_database_user',
            'PASSWORD': 'your_database_password',
            'HOST': 'localhost',
            'PORT': '5432',
        }
    }
    ```

6. Apply migrations:
    ```bash
    python manage.py migrate
    ```

7. Create a superuser for accessing the admin panel:
    ```bash
    python manage.py createsuperuser
    ```

8. Run the development server:
    ```bash
    python manage.py runserver
    ```

9. Access the app in your browser at `http://127.0.0.1:8000/`.


## 🙏 Acknowledgements

- GeeksforGeeks, especially Abhijeet Sir, for the valuable guidance and support in learning Django.
