
<h1>Hospital Management System</h1><br/>
A Java Swing-based GUI application for managing hospital operations such as adding patients, viewing patient and doctor records, and booking appointments. This application integrates with a MySQL database to store and retrieve data, ensuring efficient management of hospital information.<br/>
<br/>
**Features**<br/>
    --Add Patient: Add new patients with details like name and age.<br/>
    --View Patients: Retrieve and display a list of all patients stored in the database.<br/>
    --View Doctors: Retrieve and display a list of all doctors stored in the database.<br/>
    --Book Appointment: Schedule an appointment by selecting a doctor and patient, ensuring that the doctor is available on the specified date.<br/>
<br/>
**Technologies Used**<br/>
    --Java (JDK 8 or higher)<br/>
    --Swing for GUI<br/>
    --MySQL for database storage<br/>
    --JDBC for database connectivity<br/>
<br/>
**Prerequisites**<br/>
Before running the application, ensure that the following software is installed and configured:<br/>
    --Java Development Kit (JDK 8 or higher)<br/>
    --Download JDK<br/>
    --MySQL Database<br/>
<br/>
Download MySQL<br/>
MySQL Connector for Java<br/>
<br/>
Download Connector/J<br/>
Ensure that the MySQL JDBC driver (mysql-connector-java-<version>.jar) is added to your classpath.<br/>
<br/>
**How to Use**<br/>
        **Add Patient**<br/>
            --Go to the Add Patient tab.<br/>
            --Enter the patient’s name and age.<br/>
            --Click Add Patient to save the information to the database.<br/>
       ** View Patients**<br/>
            --Go to the View Patients tab.<br/>
            --Click View Patients to display all patients currently stored in the database.<br/>
      **  View Doctors**<br/>
            --Go to the View Doctors tab.<br/>
            --Click View Doctors to display all doctors currently stored in the database.<br/>
        **Book Appointment**<br/>
            --Go to the Book Appointment tab.<br/>
            --Enter the patient ID, doctor ID, and the desired appointment date (in the format YYYY-MM-DD).<br/>
            --Click Book Appointment to schedule the appointment.<br/>
            --If the doctor is available on the selected date, the appointment will be successfully booked.<br/>
