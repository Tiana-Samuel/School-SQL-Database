# School Database Design – SQL Table Creation & Data Insertion
This project showcases a complete school management database design using SQL. It involves creating normalized relational tables to represent core academic entities such as students, staff, schools, subjects, and parents, along with structured data insertions.

## Project Description
The SQL script demonstrates hands-on experience with database schema creation and population. The project includes table definitions with primary keys, foreign keys, constraints, and data types designed to mirror real-world school operations. It also includes sample data insertions to simulate database initialization. This project emphasizes relational database design principles including normalization, entity relationships, referential integrity, and field constraints.

## 📊 Key SQL Concepts Demonstrated
- `CREATE TABLE` for schema design
- Use of `PRIMARY KEY`, `FOREIGN KEY`, and `CHECK` constraints
- Table relationships (1-to-1, 1-to-many, many-to-many)
- `INSERT INTO` for initial data population
- `ALTER TABLE` for schema updates

## Database Entities Modeled
- **ADDRESS**: Captures location data
- **SCHOOL**: Represents educational institutions
- **STAFF**: School employees linked to schools and addresses
- **STAFF_SALARY**: Associates salaries with staff
- **SUBJECTS**: Academic disciplines
- **CLASSES**: Subjects taught by staff
- **STUDENTS**: Pupil information
- **STUDENT_CLASSES**: Links students to classes
- **PARENTS**: Guardian details linked to addresses
- **STUDENT_PARENT**: Models many-to-many relationships between students and parents

This schema can serve as a foundational model for building school management systems, academic ERDs, or practicing normalized relational database design.
