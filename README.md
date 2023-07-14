# Final-Project-C-Sharp---UNYT
Final Project C-Sharp - UNYT
In this project is implemented a management system program of our university, University of New York Tirana. The program includes three main categories in the menu, which are:

Student

Course

Score

Each of the categories have three subcategories.

The Student category includes:

Registration where we can register a new student,

Manage Student that updates the data for the students added,

Print that prints the whole information in this category.


The Course category includes:

New Course where we can add a course

Manage Course that updates the information entered for the added course,

Print that prints the all the data regarded to the Course category.


The Score category includes:

New Score where we can enter new scores for a specific student

Manage Scores that updates the scores entered

Print that prints the information about the scores.

Reports

In the implementation of the program is used the MDI inheritance form. The program includes a splash screen in the beginning, and after it, the interface login which makes possible to enter the program, checks if an account is created or not. The account in login interface is connected with the database and gets all the data from the User table. So, the account is created directly from the database. The mainForm includes all the categories of the program. Here we can access all the information such as the total of the students registered at the university, the number of male and the number of female students, also the number of the students registered to specific courses just by searching the gender. Moreover, the categories are organized using #region and #endregion that can organize the code in blocks that extend or close the main category.

Additionally, the subcategory Register, which is part of the category Student, consists of the name, last name, phone number, address, birthday, gender, and the photo of the student. Also, it includes even two buttons add and clear. Add button is to add a student in the list, whereas clear button is to automatically clear the data if the registration is canceled. This form also includes a DataGrid view to show the list of the registered students. The subcategory Manage Students is almost the same, apart from the text-box where we can search the students by their name, and also the text-box to enter the ID of the student in order to update the information. This form includes the buttons delete to delete the student and update the data, and clear to automatically delete the data. Furthermore, the interface Print consists of a DataGrid view that shows all the registered students with the relevant data. Also, there are three radio buttons1 that help to show in the DataGrid view the information of all the students (male, female), or just male students or female students. We can even just search by name only one student using text-box. The print button is for printing the information we need.

The category Course consists of three subcategories as well. The function of the New Course subcategory is to register the courses of the university. To register a course, we need the name of the course, the course hours throughout all the semester and the description of the course, if it has a special requirement or prerequisite. It also contains the button add course and clear data. Manage Course includes a grid view that shows the courses already registered. The function of this interface is to update or to delete the courses that are already there. We can search the name of the course using a text-box which works like a search button. In addition, the subcategory Print shows all the registered courses, and by using a text-box we can search the course by its name. It also includes the button Print.

At the category Score, the three subcategories of it are shown in the form of a block. The interface includes two buttons at the top of the page. The first shows the students registered in the Student category, and the other shows the grade of the students with the relevant course. To add the grade of the student we should enter the ID, select the course, enter the grade, then the letter grade. The two buttons add and clear are for adding a grade, and clearing an entered grade. Same process is followed at Manage Course subcategory too. To update the grading, we enter the ID, select the course, and enter the grade and the letter grade. We can search the course using the text-box. The button add is to add a grade, clear to automatically clear an entered grade, and update to update the whole grading data. Moreover, the Print subcategory shows the information of the student, the course and the grade in a DataGrid view. Also, is possible to search the student by entering the name.

In the category list, are also included two other categories: Dashboard and Exit. The function of Dashboard is to converse the program in its initial form. Exit helps the user to exit the program and return to login interface to log in again.

Splash Screen
![image](https://github.com/DanjaBali/Final-Project-C-Sharp---UNYT/assets/48566297/58d5cb6d-afe5-4de4-9692-9c598aa749bf)

Login Interface
![image](https://github.com/DanjaBali/Final-Project-C-Sharp---UNYT/assets/48566297/68315a80-9296-48d5-8a2b-a94f516eb93d)


Dashboard
![image](https://github.com/DanjaBali/Final-Project-C-Sharp---UNYT/assets/48566297/a2d5a084-8ef4-4a54-b1e2-fad57ec9e2bb)


Registration
![image](https://github.com/DanjaBali/Final-Project-C-Sharp---UNYT/assets/48566297/5b010cf1-bb28-4b47-8d85-3631df800544)


Manage Students
![image](https://github.com/DanjaBali/Final-Project-C-Sharp---UNYT/assets/48566297/d6f4ac7d-759e-4349-9e4d-97b02dcea5b0)


Print
![image](https://github.com/DanjaBali/Final-Project-C-Sharp---UNYT/assets/48566297/65309455-443d-4dce-81ca-a4a93e4538ed)


New Course
![image](https://github.com/DanjaBali/Final-Project-C-Sharp---UNYT/assets/48566297/792f978f-e483-4eb5-ad22-8c96d9d0398e)


Manage Course
![image](https://github.com/DanjaBali/Final-Project-C-Sharp---UNYT/assets/48566297/375c6682-2c83-4df8-b68a-4376be1afece)


Print
![image](https://github.com/DanjaBali/Final-Project-C-Sharp---UNYT/assets/48566297/2ac728e3-e51b-4e9d-8732-d5480bf7841f)

Score - Show Student
![image](https://github.com/DanjaBali/Final-Project-C-Sharp---UNYT/assets/48566297/bc9a3c72-a73b-4d15-8d1f-0e4d844a58a8)


Score - Show Grade
![image](https://github.com/DanjaBali/Final-Project-C-Sharp---UNYT/assets/48566297/3efa98e4-33f5-4888-bc63-f8967ffa0688)

Manage Score
![image](https://github.com/DanjaBali/Final-Project-C-Sharp---UNYT/assets/48566297/8125242a-307c-4cc4-b148-85f9ea0fa363)


Print
![image](https://github.com/DanjaBali/Final-Project-C-Sharp---UNYT/assets/48566297/596530f4-99d3-4a98-a100-ca755f49dbce)


Database Structure
Database of the management system for the university. It includes the Student table, the Course table, and the Score table.

![image](https://github.com/DanjaBali/Final-Project-C-Sharp---UNYT/assets/48566297/0d108b0b-f79d-46f8-8e85-406ac1e8b5de)


The Student table includes all the the students and all the informations related to them, such as first name, last name, gender,ID, birthday, phone number, address, photo.

![image](https://github.com/DanjaBali/Final-Project-C-Sharp---UNYT/assets/48566297/b5d14bc2-648d-4293-8990-7294e3f96789)


The Course table, includes information of the courses such as course Id, course name, course hours, and description of the course.

![image](https://github.com/DanjaBali/Final-Project-C-Sharp---UNYT/assets/48566297/030e98e8-6be2-46ae-9afe-38cc0bb6699b)


The Score table includes informations of students’ scores such as student ID, course hours, the grade, and the letter grade.

![image](https://github.com/DanjaBali/Final-Project-C-Sharp---UNYT/assets/48566297/24155c69-596a-45be-9198-bf329e95f269)


The User’s table contains just the user Id, the username and the password.

![image](https://github.com/DanjaBali/Final-Project-C-Sharp---UNYT/assets/48566297/af4a272f-3486-4b29-bea5-2050a4ea0329)


								    	                	May 4, 2022
Database table relationships
The User table is independent because it has no dependence to any other table.

The Student table is independent because it doesn’t have any dependency to any other table.

The Course table is also independent because it is not dependent to the other tables.

The Score table is dependent to the Student table and the Course table, because it requires the Student Id and the Course name.

Maintenance - New Features
I decided to add some new features to the project, like the study program. The 3-year program includes (Bologna system) the 4-year program includes (American system). Most changes have been made to the student class and the score class also to all forms of student and score , there is also a slight change to the main form (Dashboard).

...and it is understandable that there are changes in the database as well, mainly in the student table.

So let's see below:

UPDATED!! Dashboard
![image](https://github.com/DanjaBali/Final-Project-C-Sharp---UNYT/assets/48566297/1394c3d2-5612-47c9-b0b0-43646e1e2d6f)


In this form I have added the academic program which calculates how many systems are in the university. Below, we look at the calculation of how many students are enrolled in the 4-year system and how many in the 3-year system

UPDATED!! Registration
![image](https://github.com/DanjaBali/Final-Project-C-Sharp---UNYT/assets/48566297/e7b156d7-eb5d-4034-b40e-6883ab1d9686)

In the registration form I have added two radio buttons where the admin can choose the system desired by the student.

UPDATED!! Manage Students
![image](https://github.com/DanjaBali/Final-Project-C-Sharp---UNYT/assets/48566297/88d2cb6f-8036-4e55-975f-2312ce55ee7f)


The same thing in the manage register form, if the student wants to change the system or there was an error in the choice in this form we can update it.

UPDATED!! Score - Show Student
![image](https://github.com/DanjaBali/Final-Project-C-Sharp---UNYT/assets/48566297/11622e15-65d1-4088-b9ca-3e7285e0588d)


As we can see the change in this form is not noticeable, or more precisely we can say that a textBox is missing.

To be clear, this time I chose to calculate the grade in letters automatically because this would be more practical for the admin.

Thus, the program calculates the grade in letters for both systems automatically (note that systems have different calculations from each other)

UPDATED!! Manage Score
![image](https://github.com/DanjaBali/Final-Project-C-Sharp---UNYT/assets/48566297/5dbaaa71-83fe-4469-9290-e86a20fe2efc)


The same goes for the manage score form, if the admin wants to update something the calculation is done through the program.

UPDATED!! Print Score
![image](https://github.com/DanjaBali/Final-Project-C-Sharp---UNYT/assets/48566297/0cd3a1e3-fb6c-41ff-bb27-b2f9562e249e)


Here I made that the program in which the student is enrolled appear in gridview and the admin can search with it.

UPDATED!! Database Structure
![image](https://github.com/DanjaBali/Final-Project-C-Sharp---UNYT/assets/48566297/56d0e383-d1f2-4a23-9b5f-34e2f1704b37)


The changes I made to the database are only in the student table where I added a column to the academic program.
