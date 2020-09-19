# DB Schema and SQL applications
Designing and implementing a database schema for a course enrollment system

User Management:
1. Users can be of three types: Students, Professors, or Staff.
2. Users sign up their accounts with their email addresses.
3. Users need to set their passwords.
4. Account, password, and display names are strings.
5. One account has an optional unique display name. Users are allowed to change their display name as long as it is unique.
6. One email address can be used to register only one account.

Department Management:
1. Each department has an identifier department number.
2. Every professor is hired by one department.
3. Every staff is hired by one department.
4. Departments offer different programs, which a program can only belong to one department.
5. Students are allowed to major in different departments.
6. Students can pursue different programs, but they must major in the department which is offering that program.

Course Management:
1. Each department offers different courses.
2. A course can be opened in different semesters.
3. A semester is identified by a year and a season, e.g. 2020 Spring.
4. A course does NOT have to be opened every semester.
5. Every course has TAs, and one instructor. However, it is possible to change TAs or the instructor even during the semester.
6. An instructor must be a professor.
7. A TA must be a student.
8. A course may contain prerequisite courses.
9. A student may register in different semesters.
