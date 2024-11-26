# Hostel Management System for NSUT's 3 Girls' Hostels

## Project Overview
This Hostel Management System has been specifically designed to manage and streamline operations for the three girls’ hostels at NSUT: **Alaknanda**, **Kaveri**, and **Saraswati**. It addresses the unique requirements of these hostels while utilizing advanced database management concepts to ensure efficient and secure data handling.

## Features and Functionalities

### Core Functionalities
1. **Hostel and Room Assignment**
   - Tracks hostel attributes like air-conditioning, room types, and total number of rooms.
   - Maintains a detailed log of room occupancy and cleanliness schedules.

2. **Student Information Management**
   - Centralized Student Table stores general details such as name, age, program, and category (e.g., DASA, Outside Delhi, Transfer Case).
   - Subtype tables for students in specific hostels handle unique attributes:
     - **Alaknanda**: Records students' countries and previous residency.
     - **Kaveri**: Maintains students' CGPA and previous residency.
     - **Saraswati**: Tracks only previous residency.

3. **Visitor Management**
   - Logs details of authorized visitors, including their name, relationship to the student, and visit purpose.

4. **In/Out Tracking**
   - Tracks students' movements in and out of the hostels with timestamps and details of destinations for enhanced security.

5. **Staff Management**
   - Maintains a comprehensive record of staff, including their roles, shifts, and salaries.

6. **Complaint Management**
   - Allows students to log complaints related to plumbing, electricity, cleaning, and mess issues.
   - Tracks complaints from filing to resolution and assigns them to relevant staff.

### Key Features
- **Functional Dependency and Normalization**: The database schema ensures adherence to normalization principles to reduce redundancy and maintain data integrity.
- **Constraints, Assertions, and Triggers**: These mechanisms are implemented to enforce business rules, enhance data consistency, and automate critical updates.

## Database Design
The system is modeled using an **Entity-Relationship Diagram (ERD)**, which visually represents the relationships among the various entities, including:
- Hostels, Rooms, Students, Visitors, Staff, and Complaints.

The ERD and relational schema are designed to incorporate advanced concepts like:
- **Specialization and Generalization**: To distinguish attributes specific to Alaknanda, Kaveri, and Saraswati hostels.
- **Weak Entities**: For entities like parents that depend on others for identification.

## Documentation Provided
1. **ER Diagram**: A visual representation of the database entities and their relationships.
2. **Relational Schema**: Detailed definitions of all tables, their attributes, and relationships.
3. **Functional Dependencies and Normalization**: A comprehensive explanation of normalization levels achieved and functional dependencies.
4. **Constraints, Assertions, and Triggers**: Description of how business rules are enforced within the database.

