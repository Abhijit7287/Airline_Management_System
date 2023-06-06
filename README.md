# Airline_Management_System
---->Overview:
The Airline Management System is a comprehensive software solution developed using Java as the backend language, 
along with Java Swing for the graphical user interface (GUI), and MySQL as the database management system. 
It aims to facilitate various operations of an airline, including customer management, flight management, and ticket booking.
The system allows functionalities such as adding customers, searching customers, adding flights, booking flights, generating tickets, and managing administrators.

---->Technologies Used:

Backend Language: Java
GUI Framework: Java Swing
Database Management System: MySQL
MySQL Connector: MySQL Connector/J (JDBC driver)

---->Key Features:

Customer Management:
Add Customer: Enables the addition of customer details such as name, contact information, and frequent flyer information.
Search Customer: Allows users to search and retrieve customer details based on specified criteria.

Flight Management:
Add Flight: Allows administrators to add flight information, including flight number, departure and arrival times, seat availability, and other relevant details.
Book Flight: Enables customers to search for available flights, select seats, and make bookings.

Ticket Management:
Generate Ticket: Generates tickets for confirmed flight bookings, 
including details like passenger information, flight details, seat assignment, and other relevant data.

Administrator Management:
Add Admin: Provides the capability to add and manage administrator accounts with appropriate privileges to ensure secure system access.

---->User Interface (UI) Frames:
The UI consists of the following frames:
Main Frame: Acts as the primary container for all the existing frames in the UI.
It provides a centralized hub for navigating through different functionalities of the system.

Log In Page: Allows users to log in with their credentials to access the system.

Add Customer Page: Provides a form to input customer details and add them to the database.

Search Customer Page: Allows users to search and retrieve customer information based on specified criteria.

Add Flight Page: Enables administrators to input flight details and add them to the system.

Book Flight Page: Provides a search functionality for customers to find available flights, select seats, and make flight bookings.

Add Admin Page: Allows administrators to add new administrators to the system with appropriate access privileges.

Get Ticket Page: Displays the generated ticket for a confirmed flight booking, including passenger details, flight information, and seat assignment.

--->Schema and Tables:
The system's MySQL database includes the following tables within a dedicated schema:

Admin Table:
Stores administrator-related information such as admin ID, username, password, and access privileges.

Customer Table:
Stores customer details, including customer ID, name, contact information, and frequent flyer information.

Flight Table:
Stores flight-related information, including flight ID, flight number, departure and arrival times, seat availability, and other relevant details.

Ticket Table:
Stores ticket information for booked flights, including ticket ID, passenger details, flight details, seat assignment, and other relevant data.

---->Java Libraries:
In addition to the core Java language, the project utilizes various Java libraries to enhance its functionalities and capabilities. These libraries may include:
Java Swing Library: 
Used for developing the graphical user interface (GUI) components, such as buttons, text fields, and panels.

---->MySQL Connector/J:
To establish a connection between the Airline Management System and the MySQL database, 
the project utilizes the MySQL Connector/J library.
It serves as the JDBC driver for MySQL and facilitates seamless communication between the application and the MySQL database,
enabling data storage, retrieval, and management.
