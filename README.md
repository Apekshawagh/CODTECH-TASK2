NAME: WAGH APEKSHA VASUDEO

COMPANY: CODTECH IT SOLUTION

ID:CT6WDVH

DOMAIN: JAVA PROGRAMMING

DURATION: DEC17 2024 TO JAN17 2025

MENTOR: N.SANTHOSH

**Overview of the Project:** Library Resource Management System

This project involves developing a Java-based Library Resource Management System to manage library resources such as books, magazines, and DVDs.
The system will support essential functionalities like adding, searching, borrowing, and returning items while tracking overdue fines.
It will also implement role-based access control for librarians and patrons, ensuring secure and efficient management.

**Key Features of the Project:**


**Resource Management:**

**Add New Items:**

Librarians can add books, magazines, and DVDs with details such as title, author, category, and availability.

**Search Functionality:** Patrons and librarians can search for resources by title, author, or category.

**Categorization:** Resources are grouped into categories for easier navigation and filtering.

**Borrowing and Returning Items:**

Patrons can check out available items.

System tracks due dates for borrowed items.

Items can be returned, and their status is updated accordingly.

**Overdue Management:**

System calculates overdue fines for items returned after their due date.

Librarians can override or manage fine payments.

**User Roles:**

**Librarian Role:**

Manage library inventory (add, edit, or delete items).

View and manage overdue items and fines.

**Patron Role:**

Search for resources, borrow items, and return items.

View personal borrowing history and outstanding fines.

**Data Persistence:**

Use a database (e.g., MySQL, SQLite) or file handling to store and retrieve library data.

Ensure data integrity and persistence across program runs.

**User-Friendly Interface:**

Console-based menu or GUI for easy navigation.

Clear prompts and error messages to guide users.

**Technical Overview:**

**Programming Language:**

Java for implementation.

Optional: Use JavaFX or Swing for GUI.

Database/Storage:

Use a relational database like MySQL or SQLite for storing library data.

Alternatively, use file handling (e.g., JSON or CSV files) for smaller-scale systems.

**Design Structure:**

**Classes:**

LibraryItem (base class with common attributes like title, author, category, and availability).

Book, Magazine, DVD (subclasses with specific attributes).

User (base class for common user attributes).

Librarian and Patron (subclasses for role-specific functionality).

DatabaseHandler: Handles interactions with the database or file system.

LibrarySystem: Coordinates user input and system operations.

**Role-Based Access Control:**

Secure access to librarian functionalities (e.g., through password authentication).

**Key Algorithms:**

Searching and filtering algorithms for resource lookup.

Overdue fine calculation based on return date and due date.

**Flow of the System:**

**Authentication:**

Users log in as either librarians or patrons.

**Main Menu:**

Displays options based on the user's role.

Example:

**Librarian:** Add new items, manage inventory, view overdue fines.

**Patron:** Search resources, borrow items, return items, view history.

**Resource Management:**

Librarians can add, edit, or remove library items.

Patrons can search and borrow available items.

**Borrowing/Returning Workflow:**

Patrons select items to borrow or return.

System updates item status and calculates overdue fines if applicable.

**Data Persistence:**

Changes are saved to the database or files for future use.

**Deliverables:**

**Java Code:**

Fully implemented Library Management System.

Well-documented code with clear comments.

**Database/File Setup:**

SQL script for database setup or sample data files for file-based persistence.

**User Documentation:**

Guide for using the system, including roles and functionality.

**Optional Enhancements:**

Graphical User Interface (GUI) using JavaFX or Swing.

Exporting reports (e.g., overdue fines, borrowed items) to files.

![Screenshot (13)](https://github.com/user-attachments/assets/482d05a2-c9e2-4725-806d-02d259e61b02)

![Screenshot (14)](https://github.com/user-attachments/assets/c81655df-5d50-4cd2-81e5-7f4da7fb9ff3)

![Screenshot (15)](https://github.com/user-attachments/assets/9bbb40b0-57b5-4f9b-84f3-4bcff12c4411)

![Screenshot (16)](https://github.com/user-attachments/assets/36ba5218-8676-47a2-b83e-b16c5d453ecb)




