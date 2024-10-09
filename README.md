# Hospital Management System

## Overview

This Hospital Management System is developed using Java, JDBC, and Servlets to manage various activities in a hospital. The system allows administrators and users to interact through different functionalities, such as patient registration, doctor assignment, discharge, and more. It supports features like adding, retrieving, and managing patients, doctors, assistants, and medicines.

## Features

### Admin/Doctor Functions:

1. **Create Assistant**: Allows creating a new assistant record.
2. **Create Doctor**: Facilitates adding a new doctor to the system.
3. **Create Medicine**: Admin/Doctor can add new medicines to the inventory.
4. **Create Patient**: Registers a new patient in the hospital.
5. **Discharge**: Handles patient discharge procedures and updates records.
6. **Retrieve Doctor**: Fetches details of doctors registered in the system.
7. **Retrieve Medicine**: Fetches available medicines information.
8. **Retrieve Patients (DID)**: Retrieves patients based on their Doctor ID for specific doctor-patient associations.

### Authentication:

1. **Login**: Allows users (doctor, assistant, or admin) to log in.
2. **Logout**: Handles secure logout for users.

### Database Connection:

- **Get Connection**: Manages database connections to MySQL for all the data transactions.

## Technologies Used

### Front-End Development:

- **HTML**: To create a user-friendly interface.
- **CSS**: For styling the web pages.
- **JavaScript**: For front-end interactions and validations.
- **Bootstrap**: For responsive design.

### Back-End Development:

- **Java**: The core programming language used.
- **JDBC**: To connect and execute queries on the database.
- **Servlets**: To handle HTTP requests and responses.

### Database:

- **MySQL**: Used for storing data related to patients, doctors, medicines, and other hospital records.

## Setup Instructions

Follow these steps to set up the project locally:

1. Install Java JDK 8+ and configure it properly.
2. Download and install MySQL. Create the required database and tables as per the SQL scripts in the project.
3. Set up the project in your preferred IDE (e.g., Eclipse or IntelliJ IDEA).
4. Configure the JDBC connection in `GetConnection.java` to connect to your local MySQL instance.
5. Deploy the project on a local server (such as Apache Tomcat).
6. Use the following credentials to log in:
   - **User Login**: `mohit/Mohit`
   - **Admin Login**: `Admin/Admin`

## Functional Breakdown:

1. **CreateAssistant.java**: Servlet for creating a new assistant in the system.
2. **CreateDoctor.java**: Servlet for adding new doctor details.
3. **CreateMedicine.java**: Servlet to insert new medicine records.
4. **CreatePatient.java**: Handles patient registration.
5. **Discharge.java**: Manages patient discharge functionality.
6. **GetConnection.java**: Manages the connection to the MySQL database.
7. **Login.java**: Facilitates user login process.
8. **Logout.java**: Logs the user out and invalidates their session.
9. **RetrieveDoctor.java**: Retrieves doctor details from the database.
10. **RetrieveMedicine.java**: Retrieves information about available medicines.
11. **RetrievePatientsDID.java**: Fetches patients assigned to a specific doctor based on Doctor ID.

## Further Information

- This is a mini-project developed for educational purposes and to demonstrate the use of Java Servlets and JDBC.
- For more details, refer to the video tutorials for setup guidance:
  - [Local Setup Guide](https://youtu.be/mLFPodZO8Iw)
  - [Tender Management Setup Guide](https://www.youtube.com/watch?v=7CE3aY4e644)
