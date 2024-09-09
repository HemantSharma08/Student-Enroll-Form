# Student Enrollment Form using JsonPowerDB with API

## Description
This project is a **Student Enrollment Form** that stores data in the `STUDENT_TABLE` relation of the `SCHOOL_DB` database using JsonPowerDB (JPDB). It enables seamless CRUD operations through a user-friendly interface and API integration.

## Benefits of using JsonPowerDB
- **High Performance**: Minimal latency for real-time operations.
- **NoSQL Flexibility**: Schema-less data storage.
- **Easy API Integration**: Simplified interactions with REST APIs.
- **Cost-effective**: Lightweight and efficient for small to mid-sized projects.

## Release History
- **v1.0.0**: Initial version with form creation and API integration.

## Table of Contents
1. [Description](#description)
2. [Benefits of using JsonPowerDB](#benefits-of-using-jsonpowerdb)
3. [Release History](#release-history)
4. [Illustrations](#illustrations)
5. [Scope of Functionalities](#scope-of-functionalities)
6. [Examples of Use](#examples-of-use)
7. [Project Status](#project-status)
8. [Sources](#sources)
9. [Other Information](#other-information)

## Illustrations
Here are some screenshots showcasing the Student Enrollment Form:

### 1. Enrollment Form Interface
![Enrollment Form](./screenshots/enrollment_form.png)

### 2. Form Submission Confirmation
![Form Submission Confirmation](./screenshots/form_submission.png)

### 3. Database Structure in JsonPowerDB
![Database Structure](./screenshots/database_structure.png)

## Scope of Functionalities
- **Add Student**: Insert new records.
- **Update Student**: Modify existing records.
- **Delete Student**: Remove records.
- **Search Student**: Query based on specific criteria.

## Examples of Use
```bash
# Adding a new student
curl -X POST -H "Content-Type: application/json" -d '{"name": "John", "class": "10", "dob": "2008-01-01", "addr": "123 Street"}' http://localhost:9090/api/v1/student/add
