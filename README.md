
## Event Management API

The Event Management API is a Django-based backend system designed to manage events effectively. This API supports operations such as creating, retrieving, updating, and deleting event data, along with user authentication and comment management.

### Features

- **User Authentication**: Secure JWT authentication to access and manage the API.
- **CRUD Operations**: Full CRUD capabilities for managing events, comments, and categories.
- **Admin Interface**: Django admin configured for easy data management.
- **RESTful API**: Fully functional REST API built with Django REST Framework.

### Technologies

- **Django**: High-level Python web framework that encourages rapid development and clean, pragmatic design.
- **Django REST Framework**: Powerful and flexible toolkit for building Web APIs.
- **SQLite**: Default database used for development.
- **JWT Authentication**: Token-based authentication for the API.

### Local Setup

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/pranavc1515/event-management-api.git
   cd event-management-api
   ```

2. **Install Dependencies**:
   Ensure you have Python and pip installed, then run:
   ```bash
   pip install -r requirements.txt
   ```

3. **Apply Migrations**:
   Set up your database with:
   ```bash
   python manage.py makemigrations
   python manage.py migrate
   ```

4. **Create a Superuser**:
   To access the admin dashboard:
   ```bash
   python manage.py createsuperuser
   ```

5. **Start the Development Server**:
   ```bash
   python manage.py runserver
   ```
   Visit `http://127.0.0.1:8000/admin` to access the admin interface, and `http://127.0.0.1:8000/api/` for API endpoints.

### Usage

Use tools like Postman or cURL to interact with the API. Authenticate via the `/api/token/` endpoint to receive a JWT token and include this as a Bearer token in your API requests.

### Contributing

Contributions are welcome! Please fork the repository and submit pull requests to the main branch. For major changes, please open an issue first to discuss what you would like to change.

Ensure to update tests as appropriate.

### License

[MIT License](LICENSE)
#   e v e n t _ m a n a g e m e n t _ a p i 
 
 