# Ex03 Time Table
## Date:07.05.2025

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
        <img src="logo.png" width="1988" height="299">
        </center>
        <br>
    <table align="center" border="2"cellspacing="15"cellpadding="5">
    <caption>Timetable KANIYAMUDHAN V</caption>
    <tr bgcolor="cyan">
        <th>Day</th>
        <th>8-10</th>
        <th>10-12</th>
        <th>1-3</th>
        <th>3-5</th>
    </tr>
    <tr>
        <td bgcolor="cyan">Monday</td>
        <td bgcolor="pink">free</td>
        <td bgcolor="yellow">EVS</td>
        <td bgcolor="yellow">CN</td>
        <td bgcolor="yellow">free</td>
    </tr>
    <tr>
        <td bgcolor="cyan">Tuesday</td>
        <td bgcolor="yellow">FREE</td>
        <td bgcolor="yellow">CALCULUS</td>
        <td bgcolor="yellow">PYTHON</td>
        <td bgcolor="pink">free</td>
    </tr>
    <tr>
        <td bgcolor="cyan">Wednesday</td>
        <td bgcolor="pink">free</td>
        <td bgcolor="yellow">HUMAN VALUES</td>
        <td bgcolor="yellow">Mentor meet</td>
        <td bgcolor="pink">PYTHON</td>
    </tr>
    <tr>
        <td bgcolor="cyan">Thursday</td>
        <td bgcolor="pink">free</td>
        <td bgcolor="yellow">FREE</td>
        <td bgcolor="yellow">FREE</td>
        <td bgcolor="pink">WEB</td>
    </tr>
    <tr>
        <td bgcolor="cyan">Friday</td>
        <td bgcolor="pink">free</td>
        <td bgcolor="yellow">WEB</td>
        <td bgcolor="yellow">CALCULUS</td>
        <td bgcolor="yellow">FREE</td>
    </tr>
    <tr >
        <td bgcolor="cyan">Saturday</td>
        <td bgcolor="yellow">FREE</td>
        <td bgcolor="yellow">CN</td>
        <td bgcolor="yellow">FREE</td>
        <td bgcolor="pink">free</td>
    </tr>
</table>
    <table align="center" border="1">
        <tr>
            <th>S.NO</th>
            <th>COURSE CODE</th>
            <th>COURSE NAME</th>
        </tr>
        <tr>
            <td>1</td>
            <td>19AI414</td>
            <td>Fundamental Web Application Development(WEB)</td>
        </tr>
        <tr>
            <td>2</td>
            <td>19CS406</td>
            <td>COMPUTER NETWORK</td>
        </tr>
        <tr>
            <td>3</td>
            <td>19MA201</td>
            <td> CALCULUS AND MATRIX ALGEBRA     </tr>
        <tr>
            <td>4</td>
            <td>19HS801</td>
            <td>HUMAN VALUES</td>
        </tr>
        <tr>
            <td>5</td>
            <td>19CY801</td>
             <td>EVS</td>
        </tr>
        <tr>
            <td>6</td>
            <td>19AI301</td>
            <td>PYTHON</td>
            
        </tr>
        
    </table>
</body>
</html>
```

## OUTPUT

![alt text](<Screenshot (13).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
