# Ex03 Time Table
## Date: 10/04/2025
## Name: Praveen Raj G 
## Reg no:212224040245

## AIM
To write a html webpage page to display your slot timetable.

## ALGORITHM
### STEP 1
Create a Django-admin Interface.

### STEP 2
Create a static folder and inert HTML code.

### STEP 3
Create a simple table using ```<table>``` tag in html.

### STEP 4
Add header row using ```<th>``` tag.

### STEP 5
Add your timetable using ```<td>``` tag.

### STEP 6
Execute the program using runserver command.

## PROGRAM
<html>
    <br>
    <br>
    <table border="1" cellspacing="2" cellpadding="5" align="center">
        <caption align="center" style="color: brown;">
            <b>TIME TABLE - Praveen Raj G(24010690)</b> 
            <p>   </p>
        </caption>
        <tr>
            <th>Days</th>
            <th>Monday</th>
            <th>Tuesday</th>
            <th>Wednesday</th>
            <th>Thursday</th>
            <th>Friday</th>
        </tr>
        <tr>
            <th>8:00-10:00</th>
            <td>OS (19CS405)</td>
            <td bgcolor="yellow">FREE</td>
            <td bgcolor="yellow">FREE</td>
            <td>OS (19CS405)</td>
            <td bgcolor="yellow">FREE</td>
        </tr>
        <tr>
            <th>10:00-12:00</th>
            <td>B.EEE (19EE305)</td>
            <td bgcolor="yellow">FREE</td>
            <td bgcolor="yellow">FREE</td>
            <td>SNM (19MA211)</td>
            <td bgcolor="yellow">FREE</td>
        </tr>
        <tr>
            <th>12:00-1:00</th>
            <th>L</th>
            <th>E</th>
            <th>A</th>
            <th>V</th>
            <th>E</th>
        </tr>
        <tr>
            <th>1:00-3:00</th>
            <td>SNM (19MA211)</td>
            <td>WEB (19AI414)</td>
            <td>Mentor Meet (ECA-M)</td>
            <td bgcolor="yellow">FREE</td>
            <td>WEB (19AI414)</td>
        </tr>
        <tr>
            <th>3:00-5:00</th>
            <td>CHEM (19CY205)</td>
            <td bgcolor="yellow">FREE</td>
            <td bgcolor="yellow">FREE</td>
            <td>CHEM (19CY205)</td>
            <td>B.EEE (19EE305)</td> 
        </tr>
    </table>
    <br>
    <br>
    <br>
    <table border="1" cellspacing="2" cellpadding="2" align="center">
        <caption style="color: blue;"><b>COURSE NAME</b> <p>      </p></caption>
        <tr>
            <th>S.NO</th>
            <th>COURSE CODE</th>
            <th>COURSE NAME</th>
        </tr>
        <tr>
            <td>1</td>
            <td>19CS405</td>
            <td>OPERATING SYSTEM</td>
        </tr>
        <tr>
            <td>2</td>
            <td>19AI414</td>
            <td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
        </tr>
        <tr>
            <td>3</td>
            <td>19CY205</td>
            <td>PRINCIPLES OF CHEMISTRY IN ENGINEERING</td>
        </tr>
        <tr>
            <td>4</td>
            <td>19EE404</td>
            <td>BASIC ELECTRICAL ELECTRONIC ENGINEERING</td>
        </tr>
        <tr>
            <td>5</td>
            <td>19MA211</td>
            <td>STATISTICS AND NUMERICAL METHODS</td>
        </tr>
        <tr>
            <td>8</td>
            <td>ECA-M SCOFT</td>
            <td>MENTOR MEET</td>
        </tr>
    </table>
</html>



## OUTPUT
![Screenshot (162)](https://github.com/user-attachments/assets/dbcc7fe6-1133-4c1d-8e30-c32a491d9e48)





## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
