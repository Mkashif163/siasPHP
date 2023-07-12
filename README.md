# Student Interaction Assessment System (SIAS)

Welcome to the Student Interaction Assessment System (SIAS) project! SIAS is a PHP-based website that provides a platform for assessing student interaction and engagement. This README file will guide you through the setup process and explain the project structure.

## Table of Contents
1. [Project Overview](#project-overview)
2. [Requirements](#requirements)
3. [Installation](#installation)
4. [Configuration](#configuration)
5. [Usage](#usage)
6. [Troubleshooting](#troubleshooting)
7. [Credits](#credits)

## Project Overview
The Student Interaction Assessment System (SIAS) is designed to measure and assess student interaction and engagement during online learning. It allows teachers to create courses, upload lecture videos, track student attentiveness, and evaluate student participation through assessments.

Key Features:
- Teacher Dashboard:
  - Create and manage courses.
  - Upload lecture videos.
  - Track student attentiveness during lectures.
- Student Dashboard:
  - Join courses.
  - Access lecture videos.
  - Enable assessment mode
## Requirements
To run the SIAS project, ensure that you have the following:

- PHP (version 7 or higher)
- MySQL database
- Web server (e.g., Apache, Nginx)
- Modern web browser with JavaScript enabled
- or just install xampp to run this project

## Installation
To set up the SIAS project, follow these steps:

1. Clone the project repository to your local machine:
git clone https://github.com/Mkashif163/siasPHP

2. Move the project files to your web server's document root directory.

3. Import the database:
- Create a new database in your MySQL server.
- Import the SQL file provided with the project (`coursedb.sql`) into the newly created database. You can use a tool like phpMyAdmin or run the following command:
  ```
  mysql -u root -p your_database_name < coursedb.sql
  ```
  Enter your MySQL root password when prompted.

## Configuration
After the installation, you need to configure the project settings. Open the file `config.php` located in the project's root directory and update the following parameters:

- `DB_HOST`: The hostname of your MySQL server (usually 'localhost').
- `DB_NAME`: The name of the database you created during installation.
- `DB_USER`: The MySQL username (usually 'root').
- `DB_PASSWORD`: The password for the MySQL user (leave empty if no password is set).

Save the changes once you've updated the configuration.

## Usage
To use the SIAS project, follow these steps:

1. Start your web server.

2. Access the website by opening a web browser and entering the URL for your local server (e.g., `http://localhost/sias`).

3. Teacher Dashboard:
- Create a new account or log in if you already have one.
- Use the teacher dashboard to create courses, upload lecture videos, and evaluate student participation through assessments.

4. Student Dashboard:
- Create a new account or log in if you already have one.
- Browse available courses and join the desired ones.
- Access lecture videos and enable in assessments.

## Troubleshooting
If you encounter any issues while setting up or using the SIAS project, consider the following:

- Ensure that your PHP version meets the project requirements.
- Double-check the database configuration in `config.php`.
- Verify that the MySQL server is running correctly.
- Check the file permissions for the project files and directories.
- Make sure your web server is properly configured to serve PHP files.

If the problem persists, please refer to the project documentation or seek assistance from the project maintainers.

## Credits
The SIAS project was developed by 
Muhammad Kashif    FA19-BCS-055
Noor Ul Ain        FA19-BCS-065
Sadaf Iqbal Hashmi FA19-BCS-071

## License
COMSATS univesity islamabad, sahiwal campus
