# Ex03 Time Table
## Date:

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
~~~
<html>
    <head>
        <title>SLOT TIME TABLE</title>
    </head>
    <body>
        <center>
            <img src="Screenshot 2025-12-25 120102.png" height="100" width="540">
        </center>
        <br>
        <table align="center" bgcolor="cyan" cellspacing="2"cellpadding="4"width="750"border="5">
            <caption><b>SLOT TIME TABLE - MOHAMMED SHAMEER M (25011192)<b><caption>
            <tr align="center">
                <th bgcolor="blue">DAY/TIME</th>
                <th bgcolor="blue">MONDAY</th>
                <th bgcolor="blue">TUESDAY</th>
                <th bgcolor="blue">WEDNESDAY</th>
                <th bgcolor="blue">THURSDAY</th>
                <th bgcolor="blue">FRIDAY</th>
                <th bgcolor="blue">SATURDAY</th>
            </tr>
            <tr align="center">
                <th bgcolor="blue">8-10</th>
                <td>CRYPTO</td>
                <td>PYTHON</td>
                <td>NULL</td>
                <td>PYTHON</td>
                <td>WEB</td>
                <td>CRYPTO</td>
            </tr>
            <tr align="center">
                <th bgcolor="blue">10-12</th>
                <td>WEB</td>
                <td>Null</td>
                <td>Null</td>
                <td>Null</td>
                <td>Null</td>
                <td>Null</td>
            </tr>
            <tr>
                <th bgcolor="blue">12-1</th>
                <td colspan="6" align="center">LUNCH</td>
            </tr>
            <tr align="center">
                <th bgcolor="blue">1-3</th>
                <td>CRYPTO</td>
                <td>CRYPTO</td>
                <td>MENTOR MEET</td>
                <td>PYTHON</td>
                <td>WEB</td>
                <td>NULL</td>
            </tr>
            <tr align="center">
                <th bgcolor="blue">3-5</th>
                <td>PYTHON</td>
                <td>PYTHON</td>
                <td>WEB</td>
                <td>Null</td>
                <td>WEB</td>
                <td>Null</td>
            </tr>
        </table>
        <br>
        <table align="center" width="750" border="5" cellspacing="2" cellpadding="4" >
            <tr align="center">
                <th>S.NO></th>
                <th>SUBJECT CODE</th>
                <th>SUBJECT NAME</th>
            </tr>
            <tr align="center">
                <td>1</td>
                <td>19AI301</td>
                <td align="left">Python Programming</td>
            </tr>
            <tr align="center">
                <td>2</td>
                <td>19AI414</td>
                <td align="left">Fundamentals Of Web Application Development</td>
            </tr>
            <tr align="center">
                <td>3</td>
                <td>19CS547</td>
                <td align="left">Fundamentals Of Cryptocurrency</td>
            </tr>
            <tr align="center">
                <td>4</td>
                <td>ECA-M</td>
                <td align="left">Mentor Meet</td>
            </tr>
        </table>

    </body>
</html>
~~~

## OUTPUT
<img width="1116" height="641" alt="530154647-47c6b743-c5ca-45b2-be12-9e3dce4f1bb4" src="https://github.com/user-attachments/assets/14de38bf-f7a5-4d93-a69a-9205832d407e" />


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
