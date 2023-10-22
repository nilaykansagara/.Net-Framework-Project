# EduAdmin - School Management System

EduAdmin is a .NET Framework-based project designed for managing student and staff details, courses, and communication within an educational institution. With EduAdmin, you can streamline administrative tasks, provide a platform for staff to upload study materials, and facilitate communication between students and faculty.

## Purpose

The purpose of EduAdmin is to:

- Manage student and staff details.
- Allow staff to upload study materials for courses.
- Enable students to access course materials and ask doubts to specific faculty members.
- Allow faculty members to answer student queries.
- Empower administrators to maintain student and staff records, add courses, and delete information.

## Features

- User Authentication: Secure login system for students, staff, and administrators.
- User Roles: Three distinct roles - student, staff, and administrator.
- Course Management: Administrators can add, edit, and delete courses.
- Material Upload: Staff members can upload study materials for their courses.
- Doubt Forum: Students can ask doubts, and faculty members can provide answers.
- Staff & Student Management: Administrators can manage staff & students details.
- Feedback System: Visitors (parents/guardians) can provide feedback on the educational institution's performance. Administrators (or principal) can read and manage the feedback.
- Profile Management: Students and staff can modify their profile information.

## Prerequisites

Before running the project, ensure that you have the following dependencies installed:

- Visual Studio with .NET Framework support
- SQL Server for database management

## Installation and Setup

1. Clone the repository to your local machine:

git clone https://github.com/nilaykansagara/.Net-Framework-Project

2. Open the project in Visual Studio.

3. Set up the database:

    Create a SQL Server database.
    Import the database structure and initial data using the provided .bak (database backup) file. Follow these steps:
    a. Open SQL Server Management Studio (SSMS).
    b. Connect to your SQL Server instance.
    c. Right-click on "Databases" in the Object Explorer and choose "Restore Database."
    d. In the "Source" section, select "Device" and click the "..." button to browse for the .bak file you have. Select it and click "OK."
    e. In the "Destination" section, specify the name for your database.
    f. Click "OK" to restore the database from the .bak file.
    Update the connection string in the project's configuration file to point to the newly created database.

4. Build and run the project.

## Usage

- Access the project via your web browser at [http://localhost:PORT](http://localhost:PORT).
- Log in with appropriate credentials as a student, staff, or administrator.
- Explore the features and functionalities of EduAdmin.

## Contributing

Contributions to EduAdmin are welcome. You can contribute by forking the project, making changes, and creating pull requests. Please ensure your changes are in line with the project's goals and coding standards.

## License

This project is licensed under the [MIT License](LICENSE.md).

## Contact

If you have any questions or need assistance, feel free to contact us at kadiyamanan77@gmail.com, nilaykansagara@gmail.com.

---

We hope EduAdmin simplifies the management of your educational institution and enhances communication between students, staff, and administrators.