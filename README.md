# Library-Management-System
A comprehensive library management system built with Django, designed to streamline the process of managing books, patrons, and lending operations in a library setting.

# Features
User authentication and authorization (Librarians and Patrons)
Book management (Add, Edit, Delete, Search)
Patron management
Reservation system
Dashboard with statistics and reports

# Technologies Used
Django 4.2
Python 3.9+
SQLlite3
HTML/CSS
JavaScript
Bootstrap 5

# Installation
# # Clone the repository:
git clone https://github.com/Sivateja004/Library-Management-System.git
cd library-management-system
Create a virtual environment and activate it:
python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
Install the required packages:
pip install -r requirements.txt
Set up the PostgreSQL database and update the DATABASES configuration in settings.py.
Run migrations:
python manage.py migrate
Create a superuser:
python manage.py createsuperuser
Run the development server:
python manage.py runserver
Visit http://127.0.0.1:8000/ in your browser to access the application.

# Usage
Log in as a librarian to manage books, patrons, and lending operations.
Patrons can browse books, place reservations, and view their borrowing history.
Use the admin interface (/admin) to manage all aspects of the system.

# License
This project is licensed under the MIT License. See the LICENSE file for details.
