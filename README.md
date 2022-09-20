# Student Management System

We all know, data management has became so important over the past few years. 

Nowadays, It is not only about managing the data. In order to maintain the privacy of any user, we have had to look for an optimal & handy software which can be used in one's daily life without any issue or problems.

Few days back, I visited a college.

There, the admission process were going on. I noticed that they were using old fashioned registers to make the entry of the new student, which takes alot of time, wastes alot of paper, ink & not at all a good or healthy solution for enviorment.

I got an idea to develop something using my skills, knowledge and coding concepts.

## Here comes the concept of Student Management System.

* This software was developed in **Python** 
* Made an interactive GUI using **Tkinter**
* Added **various functions** to perform **several tasks**.
* Used **MySQL Workbench** for database, and store the data in table.
* It can be operated in **Windows**.
* The whole program was coded on **VS Code**

## Functions of Student Management System.

There's an Admin, who can perform various functions on this management system like **Add Data**, **Update Data**, **Delete Data**, **Read Data** & **Fetch Data** to ease the time taking admission process of students.

> **Add Data**
* Admin can add the **basic/personal details** of the student.
* **Unique student ID** will be alloted to **every new student**.
* **Unique student ID** has been **kept unedited**, or in **readonly format**.
* The moment admin clicks "**Add Data**" button, **Add Data** functions gets called.
  * Confirmation box occurs **asking yes/no**.
    * If user clicks "**YES**" data gets added in the table of **MySQL Workbench**.
    * Else data will not be added in the tabel.
* At the same time, "**Fetch Data**" function gets called on the same button, and data is shown on the screen.

> **Update Data**
* Admin can update the **basic/personal details** of the student.
* **Unique student ID** will be not be affected of **any updated student**.
* **Unique student ID** will remain **unedited**, or in **readonly format**.
* The moment admin clicks "**Update Data**" button, **Update Data** functions gets called.
  * Confirmation box occurs **asking yes/no**.
    * If user clicks "**YES**" data gets updated in the table of **MySQL Workbench**.
    * Else data will not be updated in the tabel.
* At the same time, "**Fetch Data**" function gets called on the same button, and data is shown on the screen.

> **Delete Data**
* Admin can delete the **basic/personal details** of the student.
* **Unique student ID** will also be deleted along with the whole record of the student.
* The moment admin clicks "**Delete Data**" button, **Delete Data** functions gets called.
  * Confirmation box occurs **asking yes/no**.
    * If user clicks "**YES**" the whole record will be deleted from the table of **MySQL Workbench**.
    * Else data will not be deleted from the tabel.
* At the same time, "**Fetch Data**" function gets called on the same button, and data is shown on the screen.

> **Fetch Data**
* Admin can fetch the **basic/personal details** of the student using the unique "**Student ID**", or "**Mobile Number**".
* Admin will be required to add the "**Student ID**", or "**Mobile Number**" of the student to fetch the corresponding data.
* The moment admin clicks "**Fetch Data**" button, **Fetch Data** functions gets called.
* At the same time, respective data is shown on the screen.

> **Read Data**
* Admin can read the **basic/personal details** of the student in there **respective columns, or fields**.
* Admin will be required to **click on a particular record** of the student which is shown on the right side of the screen.
* The moment admin clicks a record, **Read Data** functions gets called.
* At the same time respective columns, or fields will be filled with the corresponding data.

## Challenges faced in the development phase

There were **many different challenges** which I faced during the development of **Student Management System**.

With **R&D**, I managed to overcome all of them, and came up with the desired output.

But, following are the five main challenges faced.

* The first challenge was to make an interactive & simple GUI, which can be understood easily by any non-tech profile.
* The second challenge was to setup the database, and integrate the table to play with the records.
* The third challenge was to add proper exceptions, if the user fails to provide required details of the student.
* The fourth challenge was to set up a working connection string with MySQL workbench.
* The last challenge was to test, and bug hunting in the management system.

## New Features that can be seen in future

Since, it is the first working software along with database integration single handedly designed, developed & tested by me, I might be keep updating it in future to add various new features that will eventually save the time of students, and admission heads.

Some of the updates that can be seen in the project in future.

> Design Updates
* More interesting GUI will be seen in the future.
* More eye catchy color gradings, and photos.
* Some good animations, to make it look more interactive.

> Development Updates
* Fees calculations will be seen the future.
* Another screen will be added for the school, similar to college.
* More diversifications like courses, classes, sections, etc will be seen.
* Click send mail will be seen the future.
