# HAMS - Human Attention Monitoring System

HAMS is an online platform designed to monitor concentration levels of individuals in real-time. It aims to provide valuable insights into attention and focus for various scenarios, such as remote learning, online meetings, or training sessions.


## Features

- Real-time monitoring of concentration levels.
- User-friendly dashboard with visualizations.
- Historical data tracking and analytics.
- User account registration and management.
- Support for multiple user roles (admin, instructor, student, etc.).
- Customizable settings for monitoring thresholds.
- Integration with various attention monitoring devices (optional).

## Installation and Setup

1. Clone the repository:

```
git clone https://github.com/yourusername/HAMS.git
cd HAMS
```

2. Create a virtual environment and activate it:

```
python -m venv env
source env/bin/activate   # On Windows: env\Scripts\activate
```

3. Install the required dependencies:

```
pip install -r requirements.txt
```

4. Set up the database and perform migrations:

```
python manage.py makemigrations
python manage.py migrate
```

5. Create a superuser account (for admin access):

```
python manage.py createsuperuser
```

6. Run the development server:

```
python manage.py runserver
```

7. Access the application by navigating to `http://localhost:8000` in your web browser.

## Usage

1. Register as a new user or log in with an existing account.
2. Depending on your role (admin, instructor, student), you'll have different access levels and permissions.
3. Instructors can create and manage courses and track their students' concentration levels.
4. Students can join courses and view their concentration metrics on the dashboard.
5. Admins have access to user management and system settings.


