Key Features
-
- User-Centric Design: Supports students, instructors, and administrators.

- Resource Sharing: Users can upload and access learning resources.

- Collaborative Learning: Enables study groups and discussion forums within courses.

- Data Analysis: Provides insights into user engagement and course popularity through SQL queries.

Entity-Relationship Diagram (ERD)
-

The ERD illustrates the key relationships between various entities in the system. Major relationships include:

- Role → Student/Instructor (One-to-Many): Each role can be linked to multiple user accounts.

- Instructor → Course (One-to-Many): Each instructor can manage multiple courses.

- Course → Resource (One-to-Many): Each course can have multiple resources uploaded.

- Course → Study Group (One-to-Many): Each course can have multiple study groups.

- Course → Discussion (One-to-Many): Each course can host multiple discussions.

Database Implementation
-

Tools Used:
-

DB Browser: An open-source database tool used to design, prototype, and implement the database.

Tables and Relationships
-

Users: Stores details of all users (students and instructors) and their roles.

Courses: Contains information on all courses available on the platform.

Resources: Tracks resources uploaded for each course.

Study Groups: Supports the creation of study groups within specific courses.

Discussions: Facilitates course discussions with multiple participants.

SQL Queries
-

- Resource Upload: Enables users to upload files and link them to courses.

- Discussion Participation: Tracks user interactions in discussion threads.

- Study Group Creation: Allows users to create new study groups within courses.

User Story
-

Alex's Journey: Alex uploads a PDF document titled "Data_Analytics_Week1_Summary.pdf" to the Data Analytics course page. Upon noticing a discussion thread titled "Exam Preparation Tips," Alex participates in the discussion and later creates a new study group called "Data Analytics Champions" for deeper collaboration. SQL queries supporting Alex’s actions are demonstrated in the project.

Data Analysis
-

- Most Active Students: SQL queries identify users with the highest contributions (uploads, discussion posts, etc.).

- Popular Courses: Identifies the most popular courses by counting enrollments and linking instructors and students to the courses.

Reflections and Growth
-

This project fostered the following skills and competencies:

- Database Design and SQL Development: Created a robust relational database from an ERD and implemented it using SQL commands.

- Data Analysis: Used SQL queries to generate actionable insights from user interactions on the platform.

- Problem-Solving and Critical Thinking: Translated platform goals into functional database structures.

- Attention to Detail: Ensured accurate implementation of relationships, constraints, and queries.

How to Use
-
Open with DB Browser:

(or Download and install DB Browser)

Open the provided .sqlite file to explore the database schema and data.

Run SQL Queries:

Use the "Execute SQL" tab in DB Browser to run the provided SQL scripts for testing.

Future Improvements
-

User Authentication: Enhance user role management and secure access control.

Analytics Dashboard: Visualize user activity and course popularity.

Course Feedback System: Enable students to provide feedback on courses and instructors.

Author
-

Allswell Sam Obeng

Review
-
The main components of this project has been reviewed and accepted by Manisha Santhana Gopla Krishan as part of her course requirements
for the ITC6000 for the MPS in Analytics program at Northeastern University, Toronto Campus

Acknowledgments
-

DB Browser: For providing a simple and intuitive environment for database prototyping.

Draw.io: For enabling the creation of a clear and structured Entity-Relationship Diagram (ERD).
