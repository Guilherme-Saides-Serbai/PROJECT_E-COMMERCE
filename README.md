---

# E-Commerce Project

## Description

This project is an e-commerce system in development. The goal is to create a platform for online shopping, with basic functionalities initially implemented in the views.

## Features

- **Product Viewing**: Browse and view available products.
- **Shopping Cart**: Add products to the cart and proceed to checkout.
- **Admin Interface**: Manage products and orders.

## Technologies

- **Django**: Web framework for backend development.
- **Python**: Programming language.
- **SQLite**: Database (default for development).

## Setup

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/repository-name.git
   ```

2. **Create a Virtual Environment**:
   ```bash
   python -m venv venv
   ```

3. **Activate the Virtual Environment**:
   - On Windows:
     ```bash
     venv\Scripts\activate
     ```
   - On macOS/Linux:
     ```bash
     source venv/bin/activate
     ```

4. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

5. **Apply Database Migrations**:
   ```bash
   python manage.py migrate
   ```

6. **Start the Development Server**:
   ```bash
   python manage.py runserver
   ```

   Access the project at [http://127.0.0.1:8000/](http://127.0.0.1:8000/).

## Project Structure

- **`ecommerce/`**: Main project directory.
- **`ecommerce/settings.py`**: Django settings configuration.
- **`ecommerce/urls.py`**: URL configuration.
- **`ecommerce/views.py`**: Contains views for the project.
- **`ecommerce/models.py`**: Data models.
- **`ecommerce/templates/`**: HTML templates.
- **`ecommerce/static/`**: Static files (CSS, JS, images).

## License

This project is licensed under the [MIT License](LICENSE).

## Contact

- **Author**: Guilherme Saides Serbai
- **Email**: guilhermesaidesserbai@outlook.com

---
