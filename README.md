# Ex03 Time Table
## Date:16/11/2024

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
```
<html>
    <body>
        <table border="1" cellspacing="10" cellpadding="3">
            <caption>SLOT TIMETABLE-RHUDHRA PHRIYAMVADHA KS (24900189)</caption>
            <tr bgcolor="lavender">
                <th>Time/Day</th>
                <th>Monday</th>
                <th>Tuesday</th>
                <th>Wednesday</th>
                <th>Thursday</th>
                <th>Friday</th>
                <th>Saturday</th>
            </tr>
            <tr bgcolor="pink">
                <th bgcolor="lavender">8-10</th>
                <td>FS</td>
                <td>CDS</td>
                <td>FS</td>
                <td>PQC</td>
                <td>FWAD</td>
                <td>EDM</td>
            </tr>
            <tr bgcolor="pink">
                <th bgcolor="lavender">10-12</th>
                <td>EDM</td>
                <td>MAT</td>
                <td>C PRO</td>
                <td>FS</td>
                <td>C PRO</td>
                <td>PQC</td>
            </tr>
            <tr bgcolor="pink">
                <th bgcolor="lavender">12-1</th>
                <td colspan="6" align="center">LUNCH</td>
            </tr>
            <tr bgcolor="pink">
                <th bgcolor="lavender">1-3</th>
                <td>FWAD</td>
                <td>FWAD</td>
                <td>MENTOR</td>
                <td>DE</td>
                <td>FS</td>
                <td>MAT</td>
            </tr>
            <tr bgcolor="pink">
                <th bgcolor="lavender">3-5</th>
                <td>FS</td>
                <td>DE</td>
                <td colspan="4" align="center">FS</td>
            </tr>
        </table>
        <table border="1" cellspacing="5" cellpadding="2">
            <tr>
                <th>S.NO</th>
                <th>COURSE CODE</th>
                <th>COURSE NAME</th>
            </tr>
            <tr>
                <td>1</td>
                <td>19AI302</td>
                <td>Engineering design and Modelling</td>
            <tr>
                <td>2</td>
                <td>19AI304</td>
                <td>Fundamentals of C Programming</td>
            </tr>
            <tr>
                <td>3</td>
                <td>19AI414</td>
                <td>Fundamentals of Web Application Development</td>
            </tr>
            <tr> 
                <td>4</td>
                <td>19EE404</td>
                <td>Digital Electronics</td>
            </tr>
            <tr>
                <td>5</td>
                <td>19EY708</td>
                <td>Career Development Skills</td>
            </tr>
            <tr>
                <td>6</td>
                <td>19MA201</td>
                <td>Calculus and Matrix Algebra</td>
            </tr>
            <tr>
                <td>7</td>
                <td>ECA-M-SCOFT</td>
                <td>Mentor Meet</td>
            </tr>
            <tr>
                <td>8</td>
                <td>SH3214</td>
                <td>Physics for Quantum Computing</td>
            </tr>
        </table>
    </body>
</html>
```


## OUTPUT
![alt text](<logo with tt.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
