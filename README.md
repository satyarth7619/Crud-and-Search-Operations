# Django CRUD Application

This is a simple Django CRUD (Create, Read, Update, Delete) application for managing student information. The application allows users to add, view, update, and delete student records.

## Features

- Add new students
- View a list of all students
- Update existing student information
- Delete students
- Search for students by name or email

## Technologies Used

- Django
- Bootstrap
- FontAwesome

## Getting Started

Follow these instructions to get a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

Make sure you have the following installed on your system:

- Python 3.x
- Django 3.x
- Virtualenv (optional but recommended)

### Installation

1. Clone the repository

    ```sh
    git clone https://github.com/yourusername/django-crud-app.git
    cd django-crud-app
    ```

2. Create a virtual environment (optional but recommended)

    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install the required packages

    ```sh
    pip install -r requirements.txt
    ```

4. Apply migrations to set up the database

    ```sh
    python manage.py migrate
    ```

5. Run the development server

    ```sh
    python manage.py runserver
    ```

6. Open your web browser and go to `http://127.0.0.1:8000/`

## Usage

- **Add New Student**: Click on the "Add new student" button, fill out the form, and submit.
- **View Students**: All students will be listed on the main page.
- **Update Student**: Click on the edit icon next to the student you want to update, make changes in the form, and submit.
- **Delete Student**: Click on the delete icon next to the student you want to delete and confirm the deletion.
- **Search Students**: Use the search bar to find students by name or email.

## Code Overview

### `views.py`

- `index`: Handles the main functionality of the application, including listing students, adding new students, updating students, deleting students, and searching for students.

### `models.py`

- `Student`: A model representing a student with fields for `name` and `email`.

### `index.html`

- The main template that displays the list of students and includes forms for adding, updating, and deleting students.

## Contributing

Contributions are welcome! Please fork this repository and submit a pull request for any enhancements or bug fixes.

1. Fork the repository
2. Create a new branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -am 'Add new feature'`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Create a new Pull Request

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- [Django](https://www.djangoproject.com/)
- [Bootstrap](https://getbootstrap.com/)
- [FontAwesome](https://fontawesome.com/)

---

Feel free to modify and enhance this README file to better suit your project's needs. If you have any questions or need further assistance, please open an issue or contact the repository owner.

