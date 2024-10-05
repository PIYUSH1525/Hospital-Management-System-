
Hospital Management System
A Java Swing-based GUI application for managing hospital operations such as adding patients, viewing patient and doctor records, and booking appointments. This application integrates with a MySQL database to store and retrieve data, ensuring efficient management of hospital information.

Features
    --Add Patient: Add new patients with details like name and age.
    --View Patients: Retrieve and display a list of all patients stored in the database.
    --View Doctors: Retrieve and display a list of all doctors stored in the database.
    --Book Appointment: Schedule an appointment by selecting a doctor and patient, ensuring that the doctor is available on the specified date.

Technologies Used
    --Java (JDK 8 or higher)
    --Swing for GUI
    --MySQL for database storage
    --JDBC for database connectivity

Prerequisites
Before running the application, ensure that the following software is installed and configured:
    --Java Development Kit (JDK 8 or higher)
    --Download JDK
    --MySQL Database

Download MySQL
MySQL Connector for Java

Download Connector/J
Ensure that the MySQL JDBC driver (mysql-connector-java-<version>.jar) is added to your classpath.

How to Use
        Add Patient
            --Go to the Add Patient tab.
            --Enter the patient’s name and age.
            --Click Add Patient to save the information to the database.
        View Patients
            --Go to the View Patients tab.
            --Click View Patients to display all patients currently stored in the database.
        View Doctors
            --Go to the View Doctors tab.
            --Click View Doctors to display all doctors currently stored in the database.
        Book Appointment
            --Go to the Book Appointment tab.
            --Enter the patient ID, doctor ID, and the desired appointment date (in the format YYYY-MM-DD).
            --Click Book Appointment to schedule the appointment.
            --If the doctor is available on the selected date, the appointment will be successfully booked.