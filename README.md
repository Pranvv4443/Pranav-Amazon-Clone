# Amazon Clone using Django

This is a full-featured e-commerce platform inspired by Amazon, built using Django. It includes features such as user authentication, product management, shopping cart, order processing, and payment integration.

## Features
- User authentication (login, logout, registration)
- Product listing and search functionality
- Shopping cart and order management
- Secure payment integration
- Admin panel for managing products and orders
- Responsive design

## Technologies Used
- Django
- PostgreSQL/MySQL
- HTML, CSS, JavaScript
- Bootstrap
- Stripe for payments

## Installation

### Prerequisites
- Python 3.x
- pip
- Virtual environment (optional but recommended)
- PostgreSQL or MySQL (if using a database other than SQLite)

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/amazon-clone.git
   cd amazon-clone
   ```

2. Create and activate a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use: venv\Scripts\activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Configure the database in `settings.py`:
   ```python
   DATABASES = {
       'default': {
           'ENGINE': 'django.db.backends.postgresql',
           'NAME': 'yourdbname',
           'USER': 'yourdbuser',
           'PASSWORD': 'yourdbpassword',
           'HOST': 'localhost',
           'PORT': '5432',
       }
   }
   ```

5. Apply migrations:
   ```bash
   python manage.py migrate
   ```

6. Create a superuser:
   ```bash
   python manage.py createsuperuser
   ```

7. Run the development server:
   ```bash
   python manage.py runserver
   ```

8. Open your browser and visit:
   ```
   http://127.0.0.1:8000/
   ```

## Usage
- Register or log in as a user
- Browse and search for products
- Add products to the shopping cart
- Proceed to checkout and make a payment
- Manage orders from the user dashboard

## Contributing
Feel free to fork the repository and submit pull requests. Contributions are always welcome!

## License
This project is licensed under the MIT License.
