# Ex03 Time Table
## Date:15-11-2024

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
        <center>
            <img src="logo.png" width="700" height="100">
        </center>
        <table border="2" cellspacing="15" cellpadding="5" align="center">
            <caption align="center"><b><u>Slot Schedule  Elavarasan M (24900162)</u></b></caption>
            <br>
            <tr align="center" bgcolor="yellow">
                <th>Time/Date</th>
                <th>8-10</th>
                <th>10-12</th>
                <th>12-1</th>
                <th>1-3</th>
                <th>3-5</th>
            </tr>
            <tr align="center">
                <td bgcolor="yellow"><b>Monday</b></td>
                <td bgcolor="cyan">DE</td>
                <td bgcolor="cyan">C PROG</td>
                <td bgcolor="cyan">LUNCH</td>
                <td bgcolor="cyan">CHE</td>
                <td bgcolor="cyan">FREE SLOT</td>
            </tr>
            <tr align="center">
                <td bgcolor="yellow"><b>Tuesday</b></td>
                <td bgcolor="cyan">FWAD</td>
                <td bgcolor="cyan">FREE SLOT</td>
                <td bgcolor="cyan">LUNCH</td>
                <td bgcolor="cyan">DE</td>
                <td bgcolor="cyan">FREE SLOT</td>
            </tr>
            <tr align="center">
                <td bgcolor="yellow"><b>Wednesday</b></td>
                <td bgcolor="cyan">MATH</td>
                <td bgcolor="cyan">FREE SLOT</td>
                <td bgcolor="cyan">LUNCH</td>
                <td bgcolor="cyan">MEET</td>
                <td bgcolor="cyan">FREE SLOT</td>
            </tr>
            <tr align="center">
                <td bgcolor="yellow"><b>Thursday</b></td>
                <td bgcolor="cyan">EDM</td>
                <td bgcolor="cyan">MATH</td>
                <td bgcolor="cyan">LUNCH</td>
                <td bgcolor="cyan">CHE</td>
                <td bgcolor="cyan">FREE SLOT</td>
            </tr>
            <tr align="center">
                <td bgcolor="yellow"><b>Friday</b></td>
                <td bgcolor="cyan">FREE SLOT</td>
                <td bgcolor="cyan">C PROG</td>
                <td bgcolor="cyan">LUNCH</td>
                <td bgcolor="cyan">FWAD</td>
                <td bgcolor="cyan">FREE SLOT</td>
            </tr>
            <tr align="center">
                <td bgcolor="yellow"><b>Saturday</b></td>
                <td bgcolor="cyan" colspan="1">EDM</td>
                <td bgcolor="cyan">CDS</td>
                <td bgcolor="cyan">LUNCH</td>
                <td bgcolor="cyan">FWAD</td>
                <td bgcolor="cyan">FREE SLOT</td>
            </tr>
        </table>
        <br><br><br>
        <table border="2" cellspacing="10" cellpadding="3" align="center">
            <tr align="center">
                <th>S.No</th>
                <th>Course Code</th>
                <th>Course Name</th>
            </tr>
            <tr align="center">
                <td><b>1.</b></td>
                <td>19MA201</td>
                <td>Calculus and Matrix Algebra (MATH)</td>
            </tr>
            <tr align="center">
                <td><b>2.</b></td>
                <td>19EY708</td>
                <td>Career Development Skills (CDS)</td>
            </tr>
            <tr align="center">
                <td><b>3.</b></td>
                <td>19EE404</td>
                <td>Digital Electronics (DE)</td>
            </tr>
            <tr align="center">
                <td><b>4.</b></td>
                <td>19CY205</td>
                <td>Principles of Chemistry in Engineering (CHE)</td>
            </tr>
            <tr align="center">
                <td><b>5.</b></td>
                <td>19AI414</td>
                <td>Fundamentals of Web Application Development (FWAD)</td>
            </tr>
            <tr align="center">
                <td><b>6.</b></td>
                <td>19AI304</td>
                <td>Fundamentals of C Programming (C PROG)</td>
            </tr>
            <tr align="center">
                <td><b>7.</b></td>
                <td>19AI302</td>
                <td>Engineering Design and Modeling (EDM)</td>
            </tr>
            <tr align="center">
                <td><b>8.</b></td>
                <td>ECA-M-SCOFT</td>
                <td>Mentor Meet (MEET)</td>
            </tr>
        
        </table>
    </body>
</html>

```


## OUTPUT

![alt text](<Screenshot (63).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
