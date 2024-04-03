# Gymso Fitness Web Application

This web application is a simple login/register system built using HTML, CSS, JavaScript, PHP, and MySQL. It allows users to register for an account, log in, and access protected areas of the website.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [File Structure](#file-structure)
- [Database Structure](#database-structure)
- [Dependencies](#dependencies)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This project provides a web application for gym lovers. It includes frontend components for the user interface (HTML, CSS, JavaScript) and backend components for server-side processing (PHP, MySQL).

## Features

- User registration with username, email, and password
- Secure password storage using bcrypt encryption
- User login with email and password
- Validation of user inputs (e.g., email format, password strength)
- Responsive design for mobile and desktop devices
- Gym services

## Installation

1. Clone or download the project files to your local machine.
2. Set up a local server environment (e.g., XAMPP, WAMP, MAMP).
3. Import the provided SQL dump file (`login_register_pure_coding.sql`) into your MySQL database.
4. Configure the database connection in the `config.php` file.
5. Launch the application through your web server.

## Usage

1. Access the web application through your browser.
2. Register for a new account by providing a username, email, and password.
3. Log in using your registered email and password.
4. Explore the features of the application, such as accessing protected areas or logging out.

## File Structure

project/
│
├── css/
│   └── style.css
│
├── js/
│   └── script.js
│
├── includes/
│   └── config.php
│
├── images/
│   └── fit.jpg
│
├── index.php
├── register.php
├── login.php
├── logout.php
└── README.md

## Database Structure

The database consists of a single table named `users`, which stores user information:

users
│
├── id (Primary Key, Auto Increment)
├── username (VARCHAR)
├── email (VARCHAR)
└── password (VARCHAR)

## Dependencies

- jQuery: Used for DOM manipulation and event handling in JavaScript.
- AOS (Animate On Scroll) library: Used for animating elements as they scroll into view.

## Contributing

Contributions to this project are welcome. Feel free to submit bug reports, feature requests, or pull requests.

## License

This project is licensed under the MIT License.
