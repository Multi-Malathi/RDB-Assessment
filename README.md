# RDB-Assessment
Files for the RDB Assessment Tasks

Clone this folder, download the scripts in the folder and run the SQL scripts in the following order:

StudentsCoursesGen.sql
Countries.sql
ID_Types.sql
Modules.sql
Courses.sql
Students.sql
Course_has_students.sql

Run the following SQL Query to complete your first JOIN to see more information about the Students:
`SELECT Students.*, Countries.name country FROM Students INNER JOIN Countries ON Students.nationality = Countries.idCountries;`
