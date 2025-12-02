# Student-Management-System-using-C#
CourseDash is a C# web application that allows students to submit their SAT scores, intended majors, and messages for advisor review. It demonstrates strong CRUD principles, clean UI interaction, and scalable database design for academic information systems.

## Motivation
Students often need guidance when selecting a major, and advisors rely on accurate student data to provide useful direction. CourseDash was created to:
✔ Organize student academic + interest data efficiently
✔ Provide advisors quick visibility into student submissions
✔ Practice real-world relational database modeling
✔ Strengthen backend development using C#/.NET frameworks

This project highlights clean logic implementation, maintainable database interactions, and a practical student support workflow.

## Core Features (CRUD Operations)
Operation	User Action	Result
Create	Submit SAT score + major + message	Data stored in database with timestamp
Read	View all submitted entries	Organized display in a sortable table
Update	Edit an existing submission	Changes instantly reflected in UI
Delete	Remove submission by ID	Record fully deleted from system
✔ Live updates synchronized across the web interface
✔ Unique identifiers ensure reliable editing/deletion
## Database Structure (ERD)
The system uses four related tables with strong referential integrity:
### User Table
Stores student details (UserID, Name, Email)

### Majors Table
Lists approved academic majors

### SAT_SCORE Table
Holds standardized test scores linked to each user

### Submissions Table
Main entity connecting user → major → message → timestamp
<img width="1067" height="819" alt="image" src="https://github.com/user-attachments/assets/052e3c5d-b1e0-49f2-b1a1-27a267597706" />

This structure supports scale, reduces duplication, and maintains clean data relationships.

## Technology Stack
Layer	Used
Language	C#
Framework	ASP.NET
UI	Razor Pages, HTML, CSS
Data Handling	SQL Database
Optional Data	Public REST APIs

## Summary
CourseDash is a practical demonstration of:

CRUD development in C#

Database-normalized design

Optional data insights using public APIs

User-friendly academic submission workflow
Would you like me to generate a short LinkedIn post about this project as well?

