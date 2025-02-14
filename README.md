# Library-Management-System
A comprehensive library management system built with Django, designed to streamline the process of managing books, patrons, and lending operations in a library setting.

# Features
- User authentication and authorization (Librarians and Patrons)
- Book management (Add, Edit, Delete, Search)
- Patron management
- Reservation system
- Dashboard with statistics and reports

# Technologies Used
- Django 4.2
- Python 3.9+
- SQLlite3
- HTML/CSS
- JavaScript
- Bootstrap 5

# Installation
1. Clone the repository: git clone https://github.com/Sivateja004/Library-Management-System.git
2. cd library-management-system
3. Create a virtual environment and activate it:
4. python -m venv venv
5. source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
6. Install the required packages: pip install -r requirements.txt
7. Set up the PostgreSQL database and update the DATABASES configuration in settings.py.
8. Run migrations: python manage.py migrate
9. Create a superuser: python manage.py createsuperuser
10. Run the development server: python manage.py runserver
11. Visit http://127.0.0.1:8000/ in your browser to access the application.

# Usage
Log in as a librarian to manage books, patrons, and lending operations.
Patrons can browse books, place reservations, and view their borrowing history.
Use the admin interface (/admin) to manage all aspects of the system.

# License
This project is licensed under the MIT License. See the LICENSE file for details.
