

**Check-in platform for attending classes by**

**keeping a safe distance**

**General:**

The application provides the possibility to add students and classrooms (including the

maximum capacity in order to keep a safe distance).The classes will also be defined as taking

place in a certain classroom at a certain date and time period and students can register for a

certain class and date. When the maximum capacity is reached, registering is not possible

anymore. The application displays a list of classes and classrooms along with occupancy rate for

a time period.



**Main specifications:**


Multiple user roles: Guest (not logged in user), Student, Teacher, Admin.

Start page (default): calendar with classes for this week. The classes will be displayed

with minimum details: day and hour, classroom, teacher, capacity level.

As a guest, when clicking on a class you are able to see its details. All the actions are

disabled.

As a student, when clicking on a class you are able to see its details and you are able to

reserve your spot if it has free capacity.

As a teacher, when clicking on a class you are able to see its details and you are able to

edit some details (course name, classroom, etc.).

As an admin, when clicking on a class you are able to see its details and you are able to

edit all details.

As an admin / teacher, when clicking on a class you are able to see its details and you

are able to delete the item.

As an admin / teacher you have the option to click on the calendar and create a new

entry.


**Optional features:**



As an admin / teacher you have the option to click on the calendar and create a new

recurrent entry.

PDF/Excel report with the following filter criteria: time period, class, classroom, year,

section, group, etc.

As a student, when reserving your spot, you are able to select your seat in the

classroom.

Login



**Technical hints:**


The first users will be added manually in the DB, since the login feature is optional.

The current user will be mocked in a configuration file.

The interface/contract will be created first by the team. The frontend/UI will work with

mocked data until the backend is ready.

**Proposed models:** *(warning: something is missing)*

**User**:



Role – guest / student / teacher / admin

First Name

Last Name

Year (optional)

Department (optional)

Section (optional)

Group (optional)




**Class**:

Name

Teacher

Year

Section

Students

Classroom





**Classroom**:

Name

Location

Capacity

Features: whiteboard, projector, etc.


