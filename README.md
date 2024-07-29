# SchoolDatabase
## Specifications:
### constraints and Relationships:
    • The school has only 12 classes and 6 levels, One level is taught in 2 classes.
    • Each class has at maximum 40 students (so the level has at maximum 80 students and
    the school will not accept any extra students).
    • Each student studies subjects and we keep track of the year, semester, and student
    grade in each subject.
    • Any employee can park any number of cars which are described by a unique number on
    the School garage .
    • Each level has at most 2 classes , And a class is specified for one level.
    • Teacher teaches one subject , and one subject is taught by many teachers.
    • Teacher and Worker are subtypes (ISA) of Employee.
    • The student studies exactly 6 subjects per semester and one subject is studied by at
    most 80 student.
    • Each student studies in a level and we keep track of his GPA , and the level is studied by
    at most 80 students.
    • Any subject exists on only one level.


### Entities:
    • The school has students who are described by their First name, Last name, Gender, Date
    of birth, parent numbers, and a unique ID.
    • The subject is described by it's name, points, level ID and a unique ID.
    • A level is described by name and a unique ID.
    • Each level contains 12 subjects and we keep track of the semester , and a subject is
    studied in one level.
    • A class is described by its name, capacity, location, level ID and a unique class ID.
    • An Employee is described by the First name, Last name, and a unique ID and SSN
    • We keep track of teacher’s salary, and their unique Contract ID
    • We track a worker Hourly wage, Hours worked, and a derived salary.



## ER Diagram:

![WhatsApp Image 2024-07-29 at 10 54 01 PM](https://github.com/user-attachments/assets/c1537992-90fb-4cef-a923-d748ce01b8d1)



## Relational Schema:

![1](https://github.com/user-attachments/assets/aa9b23f6-d9c0-4597-b09a-1676d1e680e7)

