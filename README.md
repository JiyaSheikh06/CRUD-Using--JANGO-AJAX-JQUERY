# Django CRUD with Ajax and jQuery

This is a Django application that allows you to perform CRUD (Create, Read, Update, Delete) operations on student information using Ajax and jQuery. It provides an intuitive user interface for adding and updating student records without the need for page refresh.

## Features

- **Add Student**: You can add a new student by providing their name, email, and password. Upon submission, the student record will be saved to the database.

- **Update Student**: You can update an existing student's information by clicking the "Edit" button next to their record. The student's details will be loaded into a form, allowing you to make changes. After submitting the updated information, the record will be updated in the database.

- **Delete Student**: You can delete a student's record by clicking the "Delete" button next to their record. 

- **Show Student Information**: The application displays a table with the list of students and their details, including name, email, and password. The table is dynamically updated using Ajax and jQuery, allowing for seamless addition, modification, and deletion of records.

## Technologies Used

- Python
- Django
- HTML
- CSS
- JavaScript
- jQuery
- Ajax
- Bootstrap 5

## Installation and Usage

1. Clone the repository:

   ```shell
   git clone https://github.com/your-username/django-crud-ajax-jquery.git
   ```

2. Change into the project directory:

   ```shell
   cd django-crud-ajax-jquery
   ```

3. Set up a virtual environment (optional but recommended):

   ```shell
   python -m venv venv
   ```

4. Activate the virtual environment:

   - For Windows:

     ```shell
     venv\Scripts\activate.bat
     ```

   - For macOS/Linux:

     ```shell
     source venv/bin/activate
     ```

5. Install the project dependencies:

   ```shell
   pip install -r requirements.txt
   ```

6. Apply database migrations:

   ```shell
   python manage.py migrate
   ```

7. Start the development server:

   ```shell
   python manage.py runserver
   ```

8. Open a web browser and visit `http://localhost:8000` to access the CRUD application.

## Contributing

Pull requests and contributions are welcome! If you find any issues or have suggestions for improvement, please open an issue in the repository.

## License

This project is licensed under the MIT License. Feel free to use, modify, and distribute the code as per the license terms.

---

**Note**: Make sure to update the repository URL (`https://github.com/your-username/django-crud-ajax-jquery.git`) with your own GitHub username and repository name.

By following the steps provided in the repository, users will be able to explore and understand how to build a CRUD application using Django, Ajax, and jQuery, enabling them to implement similar functionality in their own projects.
