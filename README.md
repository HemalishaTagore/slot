# Ex03 Time Table
## Date:20.09.2025

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
    <head>
        <title>slots</title>
    </head>
    <body>
        <center><img src="logo.png" height="100" width="600"></body></center>
        <h1 align="center"><b> SLOT TIME TABLE - HEMALISHA T (25017673)</b></h1>
        <table border="1" cellpadding="10" cellspacing="5" align="center">
            <tr bgcolor="blue" >
                <th text="white"><b>DAY/TIME</b></th>
                <th><b>MONDAY</b></th>
                <th><b>TUESDAY</b></th>
                <th><B>WEDNESDAY</b></th>
                <th><b>THURSDAY</b></th>
                <th><b>FRIDAY</b></th>
                <th><b>SATURDAY</b></th>
            </tr>
            <tr>
                <td bgcolor="yellow" ><b>08.00 - 10.00</b></td>
                <td>Comm Eng</td>
                <td>Free Slot</td>
                <td>Wed</td>
                <td>Comm Eng</td>
                <td>Python</td>
                <td>Web</td>
            </tr>
            <tr>
                <td  bgcolor="yellow" ><b>10.00 - 12.00</b></td>
                <td>Free Slot</td>
                <td>Python</td>
                <td>Web</td>
                <td>Free Slot</td>
                <td>Python</td>
                <td>Python</td>
            </tr>
            <tr>
                <td  bgcolor="yellow" ><b>12.00 - 01.00</b></td>
                <td colspan="6" align="center">LUNCH</td>
            </tr>
            <tr>
                <td  bgcolor="yellow" ><b>01.00 - 03.00</b></td>
                <td>Comm Eng</td>
                <td>Comm Eng</td>
                <td>Mentors meet</td>
                <td>Comm Eng</td>
                <td>Web</td>
                <td>Web</td>
            </tr>
            <tr>
                <td  bgcolor="yellow" ><b>03.00 - 05.00</b></td>
                <td>Free Slot</td>
                <td>Free slot</td>
                <td>Python</td>
                <td>Free slot</td>
                <td>Comm Eng</td>
                <td>Free slot</td>
            </tr>
        </table>
        <br>

        <table border="5" cellpadding="15" align="center">
            <tr>
                <th>S.NO</th>
                <th>Subject Code</th>
                <th>Subject Name</th>
            </tr>
            <tr>
                <td>1</td>
                <td>19EN101</td>
                <td>English</td>
            </tr>
            <tr>
                <td>2</td>
                <td>19AL414</td>
                <td>Web application development</td>
            </tr>
            <tr>
                <td>3</td>
                <td>19AL301</td>
                <td>Python</td>
            </tr>
        </table>
    </body>
</html>
```

## OUTPUT
![alt text](<Screenshot 2025-09-20 162438.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
