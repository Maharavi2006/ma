# Ex03 Time Table
## Date:20.03.2024

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
        <title>SLOT TIMETABLE</title>
    </head>
    <body>
        <center>
            <img src="/static/logo.png" height="100" width="540">
        </center>
        <br>
        <table align="center" width="540" cellspacing="2" cellpadding="4" border="5" bgcolor="red"</table>
        <caption><b>SLOT TIME TABLE-Mahalakshmi
            <br>
            register no :212223230117
        </b></caption>
        <tr align="center">
        <th bgcolor="blue">Day/Time</th>
        <th bgcolor="blue">Monday</th>
        <th bgcolor="blue">Tuesday</th>
        <th bgcolor="blue">Wednesday</th>
        <th bgcolor="blue">Thursday</th>
        <th bgcolor="blue">Friday</th>
        </tr>
        <tr align="center">
        <th bgcolor="yellow">8-10</th>
        <th rowspan="2">FREE SLOT</th>
        <td>Statistics</td>
        <td>FREE</td>
         <td>digital electronics</td>
         <td>Fundamentals of web</td>
        </tr>
        <tr align="center">
            <th bgcolor="yellow">10-12</th>
            <td>FREE</td>
            <td>python</td>
            <td>BEEE</td>
            <td>FREE SLOT</td>
            </tr>
        <tr align="center">
                <th bgcolor="yellow">12-1</th>
                <td colspan="5">LUNCH BREAK</td>
                
                </tr>  
                <tr align="center">
                    <th bgcolor="yellow">1-3</th>
                    <td>BEEE</td>
                    <td>Fundamentals of web</td>
                    <td>EMPD</td>
                   <td rowspan="2">FREE SLOT</td>
                    <td>Creative skill</td>
                    </tr>         
                    <tr align="center">
                        <th bgcolor="yellow">3-5</th>
                        <td>Digital electronics</td>
                        <td>FREE</td>
                        <td>linaear algebra</td>
                        <td>FREE SLOT</td>
                        
                        </tr>    
                    </table>
                    <br>         

<table align="center" width="540" cellspacing="2" cellpadding="4" border="5"</table>
<tr>
    <td>s.no</td> <td>subject code</td> <td>subject name</td>
</tr>
<tr>
    <td>1</td> <td>19AI301C</td>   <td>Python linear algebra</td>
</tr>
<tr>
    <td>2</td>  <td>19AI414</td>  <td>Fundamentals of web</td>
</tr>
<tr>
    <td>3</td> <td>19EE305</td>   <td>Basic Electrical Electronics and Measurement Engineering</td>
</tr>
<tr>
    <td>4</td>  <td>19EE404</td> <td>Digital Electronics</td>
</tr>
<tr>
    <td>5</td> <td>19EY702</td>  <td>Creative skills</td>
</tr>
<tr>
    <td>6</td> <td>19AI303</td>  <td>Engineering Mechanics and product development </td>
</tr>
<tr>
    <td>7</td> <td>19MA211</td>  <td>Statistics and Numericals</td>
</tr>
</table>

</body>
</html>
```

## OUTPUT
#![alt text](<Screenshot 2024-03-20 194510.png>)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
