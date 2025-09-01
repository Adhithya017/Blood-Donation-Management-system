# Blood Donation Management System

This is a web-based management system designed to connect voluntary blood donors with hospitals and patients in need. The application provides a seamless platform for donor registration, blood request management, and searching for compatible blood donors.

## Features

* **Donor Registration:** A user-friendly form for new donors to register their details, including personal information, contact details, and blood group.
* **Donor Search:** A powerful search function that allows hospitals or users to find available donors based on blood group and location.
* **User Authentication:** Secure login and logout functionality for registered users.
* **Profile Management:** Donors can update their contact and personal details.
* **Suggestion/Contact Form:** A dedicated page for users to submit suggestions or general inquiries.
* **Responsive Design:** The application is built with a responsive layout to ensure it works well on both desktop and mobile devices.

## Requirements

To run this project on your local machine, you will need to set up a web server environment. The project was developed and tested using **XAMPP**.

* **XAMPP** (or a similar environment like WAMP/MAMP)
* **PHP** (version 7.0 or higher recommended)
* **MySQL**
* A modern web browser

## Installation and Setup

Follow these steps to get the project up and running on your local machine.

### 1. Clone the Repository

First, clone this GitHub repository to your local machine using Git.


git clone [https://github.com/your-username/Blood-Donation-Management-system.git](https://github.com/your-username/Blood-Donation-Management-system.git)

2. Set Up the Project Folder
Move the entire Blood-Donation-Management-system folder into your XAMPP's web root directory. The default path is:

Windows: C:\xampp\htdocs\

macOS: /Applications/XAMPP/htdocs/

3. Start Apache and MySQL
Open the XAMPP Control Panel and click Start for both the Apache and MySQL services.

4. Create the Database
Open your web browser and navigate to http://localhost/phpmyadmin.

Click on the Databases tab and create a new database.

Name the database bld_dntn.

5. Import the Database Schema
With the bld_dntn database selected, click on the Import tab.

Click Choose File and select the bld_dntn.sql file from the sql/ directory within your project folder.

Click Go to import the database tables.

Open the DB_conn.php file in your project directory and ensure the database connection details are correct. For a standard XAMPP setup, they should be as follows:

$hostname = "localhost";
$username = "root";
$password = "";
$database = "bld_dntn";

7. Run the Project
You are now ready to run the project. Open your web browser and navigate to the following URL:
http://localhost/Blood-Donation-Management-system/

Contact
For any questions or suggestions regarding the project, feel free to contact me.

##Snapshots:

<img width="1912" height="1068" alt="Screenshot 2025-09-01 160307" src="https://github.com/user-attachments/assets/a0846576-bad3-4281-88f7-9c68c68c4281" />

<img width="1909" height="1071" alt="Screenshot 2025-09-01 160339" src="https://github.com/user-attachments/assets/932d884f-753e-47e0-bb62-ef117b17e005" />

<img width="1904" height="1065" alt="Screenshot 2025-09-01 160421" src="https://github.com/user-attachments/assets/aaa3d54a-a4b8-4ea4-8428-08dfd966c5de" />

<img width="1917" height="971" alt="Screenshot 2025-09-01 160438" src="https://github.com/user-attachments/assets/e7d17182-30b2-4280-aab4-33ae2998f15f" />




