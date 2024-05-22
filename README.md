# Online-Voting-System-
Online Voting System
Online Voting System is a web-based application designed to facilitate electronic voting processes for various purposes, such as elections, surveys, or polls.

Technologies Used
Frontend: HTML, CSS, some JavaScript
Backend: PHP
Database: MySQL
Installation
Install XAMPP.
Open the XAMPP Control Panel and start Apache and MySQL.
Download the project from GitHub: Online-Voting-System.
Extract the files to C:\xampp\htdocs.
Open your browser and visit http://localhost/Online-Voting-System/index.php to get started.
Database Setup
Open localhost/phpmyadmin in your browser.
Click on New in the side navbar.
Give a database name (e.g., votingsystem) and hit the Create button.
Create a table named userdata with the following attributes:
id (int 11) [PRIMARY KEY]
username (varchar 100)
mobile (varchar 20)
password (varchar 100)
photo (varchar 100)
standard (enum ‘candidate’, ‘voter’)
status (int 11)
votes (int 11)
About Online Voting System
This PHP-MySQL backend application provides the following features:

Secure and user-friendly web app for efficient voting
Real-time updates
Admin panel
Vote verification
Customizable
