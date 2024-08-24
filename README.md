# Krishi-seva-Management-System
 This is Krishi Seva management System project which is made using HTML, CSS, Java Script, PHP .

Krishi Seva Management System is a comprehensive platform designed to help farmers and agricultural stakeholders manage various aspects of farming operations effectively. This project is built using HTML, CSS, JavaScript, and PHP and integrates multiple services that cover everything from crop and livestock management to financial and marketing solutions.

Table of Contents
Project Overview
Features
Installation
Usage
Database Schema
Contributors
License
Project Overview
The Krishi Seva Management System provides a centralized system for farmers, suppliers, workers, and administrators to handle their day-to-day agricultural activities. It offers crop monitoring, livestock management, financial tracking, marketing, and other essential services needed in agriculture. It also includes dashboards for farmers, suppliers, and administrators to manage resources efficiently.

Features
Crop Management: Track crop planting, growth, and harvesting with tools to monitor pest control, fertilization, and other critical aspects.
Livestock Management: Manage the breeding, feeding, and health of livestock with an intuitive interface.
Financial Management: Record and manage financial transactions, such as expenses, revenues, and loans.
Inventory Management: Keep track of farm inventory like seeds, fertilizers, and machinery.
Worker Management: Farmers can hire workers and manage their tasks efficiently.
Weather Reports: Get updated weather reports relevant to your location for better decision-making.
Government Schemes: Explore and manage available government schemes tailored to agricultural development.
Marketing and Sales: Tools to assist farmers in marketing their products and tracking sales.
Installation
Clone the repository:

bash
Copy code
git clone https://github.com/addygupta21/Krishi-Seva-Management-System.git
Set up the database:

Import the Final_Agri_Database.sql file into your MySQL database server. It contains all necessary tables and data.
Configure the database connection:

Modify the db_connect.php file to include your database connection details.
Ensure your web server has support for PHP and MySQL. You can use XAMPP, WAMP, or LAMP depending on your OS.

Usage
After setting up the system, navigate to the home page of the system via your local server (e.g., http://localhost/Krishi-Seva-Management-System/).
From the homepage, you can register as a farmer or worker. Administrators can log in through the Admin Login page.
Access dashboards for managing crop information, livestock, finances, workers, and more.
Farmers can request loans, manage crop yields, and view government schemes through their dashboards.
Administrators can manage users, handle complaints, approve loans, and more.
Database Schema
The application uses a MySQL database with several key tables:

admin_register: Stores information about administrators.
farmer_register: Holds details of registered farmers.
crop: Contains information about crops managed by farmers.
loan_request: Handles loan requests submitted by farmers.
worker_register: Stores worker profiles and details.
worker_approval: Manages the worker approval and assignment process.
scheme: Tracks government schemes available for farmers.
You can find more details in the Final_Agri_Database.sql file.

Contributors
Addy Gupta: addygupta21 Sagar Gupta: sgishere
Open to contributions from the community. Feel free to fork the repository and submit pull requests.
License
This project is licensed under the MIT License - see the LICENSE file for details.

