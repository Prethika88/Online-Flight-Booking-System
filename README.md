## Overview
- The Online Flight Booking System is a web-based application built with PHP and MySQL that allows users to search for flights, book tickets, and manage their bookings easily.
- It also provides an admin panel to manage flights and users efficiently.
- The system is secure, user-friendly, and demonstrates core web development concepts like server-side scripting, database management, and front-end integration.
  
## Features
- User registration and login.
- Search flights by source, destination, and date.
- Book tickets and view booking history.
- Admin panel to manage flights and bookings.
- Secure password storage and authentication.
- Responsive design for desktop and mobile.
  
## Technologies Used

- Backend: PHP

- Frontend: HTML, CSS, JavaScript

- Database: MySQL

- Server: XAMPP (Apache + MySQL)

## Installation

1. Clone this repository:

   git clone https://github.com/Prethika88/Online-Flight-Booking-System.git

2. Move the project folder to your XAMPP htdocs directory:

   C:\xampp\htdocs\

3. Start Apache and MySQL from the XAMPP control panel.

4. Open your browser and go to:

   http://localhost/Online-Flight-Booking-System/

## Database Setup

1. Open phpMyAdmin (http://localhost/phpmyadmin/ ).

2. Create a new database named flight_booking.

3. Import the database.sql file from the project to create the required tables.

4. Update the database connection in config.php:

   $host = "localhost";

   $user = "root";

   $password = "";

   $dbname = "flight_booking";

## Usage

- Register as a new user or login with an existing account.

- Search available flights using the search form.

- Select a flight and book tickets.

- View your booking history in the "My Bookings" section.

- Admins can login with admin credentials to manage flights and users.
