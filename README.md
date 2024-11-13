# Event Management System

An Event Management System built with PHP and MySQL that enables users to manage and participate in college events. This project includes features for event creation, registration, chat functionality, and an admin dashboard.

## Table of Contents
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Screenshots](#screenshots)
- [License](#license)

## Features
- **Admin Dashboard**: Manage events, users, and view event details.
- **User Registration**: Allows users to register and log in to the platform.
- **Event Management**: Users can view, join, or cancel event registrations.
- **Chat Feature**: Real-time chat functionality for event participants.
- **Database Management**: SQL script to set up the required database schema.

## Technologies Used
- **Programming Languages**: PHP, HTML, CSS, JavaScript
- **Database**: MySQL (SQL script included)
- **Frameworks & Libraries**: Bootstrap (for styling, if included)
- **Other**: AJAX (for asynchronous data fetching in chat)

## Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/SarayuGangula/EventManagementSystem.git
    cd EventManagementSystem
    ```

2. **Database Setup**:
   - Import the SQL file `college_event_management.sql` into your MySQL database.
   - Update the database credentials in `db_connection.php` with your local MySQL credentials.

3. **Start a Local Server**:
   - Place the project files in the server's root directory (e.g., `htdocs` if using XAMPP).
   - Start Apache and MySQL servers (if using XAMPP or WAMP).

4. **Access the Application**:
   - Open your browser and go to `http://localhost/EventManagementSystem`.

## Usage

1. **Admin**:
   - Navigate to the admin dashboard by accessing `/admin_dashboard.php`.
   - Login as an admin (default credentials can be set in the database).
   - Manage events, view users, and oversee event details.

2. **User**:
   - Register a new account and log in.
   - Browse available events, join or leave events, and chat with other participants.
  


