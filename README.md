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


## Benefits of using JsonPowerDB
1. **Simplified Database Access**: JsonPowerDB makes data retrieval and storage straightforward without complex queries.
2. **NoSQL and Flexible Schema**: It allows for dynamic schema changes, making it ideal for agile development environments.
3. **Efficient and High Performance**: Optimized for faster response times, even with large datasets.
4. **Built-in RESTful APIs**: Seamless integration with frontend applications through built-in RESTful APIs.
5. **Minimal Setup and Easy to Use**: JsonPowerDB doesn’t require complex configurations, making it easier to integrate into projects.


## Illustrations
Here are some screenshots showcasing the Student Enrollment Form:

### 1. Enrollment Form Interface
![Screenshot 2024-09-09 224535](https://github.com/user-attachments/assets/7e5a97e9-1d41-4cfc-ad25-0d39e2e597d3)


### 2. JSONPowerDB
![Screenshot 2024-09-09 224646](https://github.com/user-attachments/assets/57fffd16-cc52-46f7-9306-b6b6c16f06e1)


### 3. Database Structure in JsonPowerDB
![Screenshot 2024-09-09 224554](https://github.com/user-attachments/assets/25767690-f4e2-4b46-8bac-61a624c87d85)


## Scope of Functionalities
- **Add Student**: Insert new records.
- **Update Student**: Modify existing records.
- **Delete Student**: Remove records.
- **Search Student**: Query based on specific criteria.

## Examples of Use
```bash
# Adding a new student
curl -X POST -H "Content-Type: application/json" -d '{"name": "John", "class": "10", "dob": "2008-01-01", "addr": "123 Street"}' http://localhost:9090/api/v1/student/add
