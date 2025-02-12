# To Do List App

## Overview

The To Do List App is a simple web application that allows users to manage their tasks efficiently. Built using PHP and MySQL, this app provides a user-friendly interface to add, edit, delete, and view tasks. The application runs on a local server using XAMPP and utilizes phpMyAdmin for database management.

## Features

- Add new tasks
- Edit existing tasks
- Delete tasks
- Mark tasks as completed
- View all tasks in a list format
- Simple and intuitive user interface

## Prerequisites

Before you begin, ensure you have the following installed on your machine:

- [XAMPP](https://www.apachefriends.org/index.html) (includes Apache, MySQL, and PHP)
- A web browser (e.g., Chrome, Firefox)

## How to Run the To Do List App

Follow these steps to run the To Do List App on your local machine:

### Step 1: Install XAMPP

1. **Download XAMPP:**
   - Go to the [XAMPP website](https://www.apachefriends.org/index.html) and download the version suitable for your operating system.

2. **Install XAMPP:**
   - Run the installer and follow the installation instructions. Make sure to install Apache and MySQL components.

### Step 2: Download the To Do List App

1. Extract the ZIP file

2. Download the GitHub Repository


### Step 3: Move the Project to XAMPP's `htdocs`

1. **Locate the `htdocs` Directory:**
   - Navigate to the XAMPP installation directory (usually `C:\xampp\htdocs\` on Windows).

2. **Copy the Project Folder:**
   - Move the downloaded project folder (e.g., `todo-list-app`) into the `htdocs` directory.

### Step 4: Start XAMPP

1. **Open XAMPP Control Panel:**
   - Launch the XAMPP Control Panel.

2. **Start Apache and MySQL:**
   - Click the "Start" buttons next to both Apache and MySQL modules. Ensure both services are running (indicated by green lights).

### Step 5: Create the Database

1. **Open phpMyAdmin:**
   - In your web browser, navigate to `http://localhost/phpmyadmin`.

2. **Create a New Database:**
   - Click on the "Databases" tab.
   - Enter `todo_list` as the database name and click "Create".

3. **Import the SQL File:**
   - Select the newly created `todo_list` database.
   - Click on the "Import" tab.
   - Click "Choose File" and select the `database.sql` file located in the project folder.
   - Click "Go" to import the database structure and initial data.


### Step 6: Access the Application

1. **Open the Application:**
   - In your web browser, navigate to:
     ```
     http://localhost/To-do-List-main/index.php
     ```

2. **Using the App:**
   - You should see the To Do List interface. You can now add, edit, delete, and manage your tasks.



### Troubleshooting

- **If you encounter issues:**
  - Ensure that Apache and MySQL are running in the XAMPP Control Panel.
  - Check that the database name in `config.php` matches the name you created in phpMyAdmin.
  - Make sure there are no syntax errors in your PHP files.

## Technologies Used

- PHP
- MySQL
- HTML/CSS
- JavaScript (optional for enhanced interactivity)

## Contributing

Contributions are welcome! If you have suggestions for improvements or new features, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any questions or feedback, please contact:

- Your Name
- Your Email
- Your GitHub Profile

---

Thank you for using the To Do List App! Happy task managing!
``
