
# Student result management system

    This is one of my personal project, "Student result management system". which is built by Java, JFrames, Mysql.  


## Project description
    this project "Student result management system", which is built by the following techs. helps universities or schools to manage and do operations on students marks & results.
### Techs used :
    1. Java
    2. Java Frames
    3. JDBC
    4. MySQL

### Modules :
#### Admin
    * Admin page is secured with username & password. One with proper credentials can only log in.
    * After a successful login,admin page will appear.where one can,
        - add student's bio, result,
        - view registered  students, registered students result.
    * all of these data are stored in form table(student table,result table) in MySQL. 
    * MySQL is connected to this project using JDBC.

#### Student
    * Here, a registered student can check his/her result, by entering their roll no.
    * After a correct registered roll no is entered,the result page will appear.
    * The Student result page contains two sections,
        - Upper section => Student's details (i.e.. roll no,name father name, course,branch..etc)
        - Lower section => Student's marks of each subject, total marks scored by student, pass marks of each subject.
    
## How to run
    1 - install these
        * Java SE Development Kit 8 (JDK 8).
        * After installing JDK 8, install NetBeans IDE.
        * mysql-installer-community-8.0.34.0
        * mysql-connector-j-8.1.0
        * rs2xml(.jar file).

    2. Open NetBeans IDE. Click on File -> Open Project and browse to the downloaded folder named "result management" and select it. It will load the NetBeans project.
    3. Open MySQL ,create a database as "srm" and create tables as,
        * student(rollno,name,gender,fathername,course,branch),
        * result((rollno,python,dbms,networks,maths,os)).
    4. Include mysql connector and rs2xml.jar into our project library and now good to go.
    5. Now run the project, click admin button and on login page, enter credentials ( username: admin , password: admin ).
    6. Now user can add student, result and view registered students,results.
    7. Then click student button on homepage,then enter registered student rollno.
    8. Finally the result page will appear.
## Screenshots
![homepage](https://github.com/pranav-3005/student-result-management-system/assets/113624768/8e50166f-f3e9-418c-a78b-6559853732a6)

![admin login](https://github.com/pranav-3005/student-result-management-system/assets/113624768/4d60109e-cff2-440d-90e3-47d3da9866bd)

![add student result](https://github.com/pranav-3005/student-result-management-system/assets/113624768/8932bf48-fefe-4381-ba2b-f4f0daff0139)

![view all results](https://github.com/pranav-3005/student-result-management-system/assets/113624768/9db63879-4720-411b-b9ac-e56f17064407)

![search rollno](https://github.com/pranav-3005/student-result-management-system/assets/113624768/deedc987-6c85-44ef-b52e-3147aca320d2)

![result page](https://github.com/pranav-3005/student-result-management-system/assets/113624768/54a9e4c7-e184-4597-af1c-724785bba4c5)

db:
![db](https://github.com/pranav-3005/student-result-management-system/assets/113624768/496c2b13-2a3e-449d-add4-06caa2ca33e5)









