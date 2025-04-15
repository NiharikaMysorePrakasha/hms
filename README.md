# Hospital Management System

A web-based Hospital Management System that simplifies and streamlines patient registrations, appointment bookings, and medical history management. Built with PHP and MySQL, this system offers separate portals for patients, doctors, and administrators, ensuring a seamless experience across all user types.

## Project Abstract

The Hospital Management System (HMS) is designed to digitize and enhance hospital operations by allowing patients to register, book appointments, and track medical history online. Doctors and admins can manage appointments, patient details, and provide timely healthcare services efficiently. This project addresses the gap between hospital services and digital convenience, improving the patient experience and operational workflow.

## Project Overview

The HMS portal provides the following major functionalities:

- **Patient Portal**:
  - Registration & login
  - Appointment booking with doctors
  - View appointment history
  - View and manage medical records
  - Reset/change passwords and update profiles

- **Doctor Portal**:
  - Secure login
  - Access to appointment schedule
  - Review patient medical history

- **Admin Portal**:
  - Manage doctors and patient accounts
  - View all appointments
  - Oversee medical history logs

## Tech Stack

| Category        | Tools/Technologies Used             |
|----------------|--------------------------------------|
| Frontend       | HTML, CSS                           |
| Backend        | PHP (Core PHP)                      |
| Database       | MySQL                               |
| Server         | Apache (XAMPP/WAMP)                 |
| Version Control| Git                                 |

## Tools Used

- **XAMPP/WAMP** – Local server environment
- **VS Code / Sublime Text** – Code editor
- **phpMyAdmin** – Database management
- **GitHub** – Version control and project repository

## Functional PHP Files

The core PHP files used in the project are:

- `registration.php` – New patient registration  
- `user-login.php` – Patient login page  
- `book-appointment.php` – Book new appointments  
- `appointment-history.php` – View patient’s past appointments  
- `manage-medhistory.php` / `view-medhistory.php` – Medical records interface  
- `change-password.php` / `change-emaild.php` – Profile settings  
- `forgot-password.php` / `reset-password.php` – Account recovery  
- `dashboard.php` – Common user dashboard  
- `logout.php` – Session handling  
- `get_doctor.php` – Retrieve doctor data dynamically  
- `check_availability.php` – Check appointment availability

## Dataset

No third-party medical datasets are used. Data is entered by users and managed through the interface, and stored securely in a **MySQL** database schema with tables such as:

- `users`
- `appointments`
- `doctors`
- `medical_history`
- `admin`

## Future Scope

- Integration of **E-prescription generation**
- Addition of **Appointment reminders**
- **Real-time doctor availability** using AJAX
- Support for **multi-specialty hospitals**
- Integration with **telemedicine/video consultation modules**
- Use of **Laravel or Django** for enhanced security and scalability

## Outcome Snapshot

https://github.com/NiharikaMysorePrakasha/hms/blob/main/Outcome.png


