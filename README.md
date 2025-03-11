# Django Car Dealership App

The **Django Car Dealership App** is a web-based platform designed for car dealerships to manage vehicle inventory, customer inquiries, and sales efficiently. This project leverages Django's robust backend capabilities to deliver a seamless experience for both administrators and customers.

## Features

- **Vehicle Listings** – Add, update, and remove car listings.
- **Customer Inquiry Management** – Handle customer inquiries and responses.
- **User Authentication** – Secure login and registration system.
- **Admin Dashboard** – Manage inventory and track sales.
- **Search and Filter** – Users can search and filter available cars.
- **Responsive UI** – Mobile-friendly design with Bootstrap.

## Technologies Used

- **Django** – Web framework for backend development.
- **HTML5 & CSS3** – Frontend structure and styling.
- **Bootstrap** – Responsive UI design.
- **JavaScript** – Interactive functionalities.
- **SQLite** – Default database (can be switched to PostgreSQL or MySQL).

## Project Structure

```
Django-Car-Dealership-App/
├── dealership/         # Core application handling cars and inquiries
├── static/             # CSS, JavaScript, and image files
├── templates/          # HTML templates
├── db.sqlite3          # SQLite database
├── manage.py           # Django management script
├── requirements.txt    # Project dependencies
├── runtime.txt         # Python runtime environment
```

## Getting Started

Follow these steps to set up the project locally:

### 1. Clone the Repository

```bash
git clone https://github.com/HSk2703/Django-Car-Dealership-App.git
cd Django-Car-Dealership-App
```

### 2. Create and Activate a Virtual Environment

```bash
python -m venv env
```

#### On Windows:
```bash
env\Scripts\activate
```

#### On macOS/Linux:
```bash
source env/bin/activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Apply Migrations

```bash
python manage.py migrate
```

### 5. Run the Development Server

```bash
python manage.py runserver
```

### 6. Access the Application

Open your browser and navigate to:

👉 [http://127.0.0.1:8000/](http://127.0.0.1:8000/)

## Contributing

Contributions are welcome! To contribute:

1. **Fork the repository**.
2. **Create a new branch** for your feature or bug fix.
3. **Commit your changes** with a clear message.
4. **Push your changes** to your forked repository.
5. **Submit a pull request** with details of your changes.

## License

This project is licensed under the **Apache-2.0 License**. See the `LICENSE` file for more details.

