# Ex03 Time Tabclearle
## Date:8.03.2025

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
<title>Slot Timetable</title>
</head>
<body>
    <center>
        <img src="/static/logo.png" height="100" width="540">
    </center>
    <br>
    <table align="center" width="540" cellspacing="2" cellpadding="4" border="5" bgcolor="cyan">
    <caption><b>SLOT TIME TABLE-REVATHI.S(212224230228)</b></caption>
    <tr  align="center">
    <th bgcolor="pink">Day/Time</th>
    <th bgcolor="pink">Monday</th>
    <th bgcolor="pink">Tuesday</th>
    <th bgcolor="pink">Wednesday</th>
    <th bgcolor="pink">Thursday</th>
    <th bgcolor="pink">Friday</th>
    <th bgcolor="pink">Saturday</th>
    </tr>
    <tr align="center">
    <th  bgcolor="pink">8-10</th>
        <td>Web development</td>
        <td>Task completion</td>
        <td>Assessment hour</td>
        <td>Task presentation</td>
        <td>Task completion</td>
        <td rowspan="6" style="text-align:center;">Module<br>assessment<br>completion</td>


    </tr>
    <tr align="center">
        <th  bgcolor="pink">10-12</th>
            <td>Task assignment</td>
            <td>Web development</td>
            <td>Task presentation</td>
            <td>Module completion</td>
            <td>Web development</td>
           
    
        </tr>
        <tr align="center">
            <th bgcolor="pink">12-1</th>
            <td colspan="5" style="text-align:center;">Lunch Hour</td>

        </tr>
        <tr align="center">
            <th  bgcolor="pink">1-3</th>
                <td>Fundamentals of AI</td>
                <td>Module completion</td>
                <td>Mentors meet</td>
                <td>Fundamentals of AI</td>
                <td>Task completion</td>
        
        
        </tr>
        <br>
        
        <table align="center" cellspacing="2" cellpadding="4" border="2" style="margin-top:20;">
        <tr align="center">
        <th>S.No.</th>
        <th>Subject Code</th>
        <th>Subject Name</th>


        </tr>
        <tr>
        <td align="center">1.</td>
        <td align="center">19AI414</td>
        <td align="center">Fundamentals of web development</td>
       </tr>
       <tr>
        <td align="center">3.</td>
        <td align="center">19EE404</td>
        <td align="center">Digital electronics</td>
       </tr>
       <tr>
        <td align="center">4.</td>
        <td align="center">19AI305</td>
        <td align="center">Advanced c programming</td>
       </tr>
       <tr>
        <td align="center">5.</td>
        <td align="center">19MA220</td>
        <td align="center">Maths for AI</td>
       </tr>
       <tr>
        <td align="center">6.</td>
        <td align="center">19PH214</td>
        <td align="center">Physics for Quantum computing</td>
       </tr>
       <tr>
        <td align="center">7.</td>
        <td align="center">19MA221</td>
        <td align="center">Linear Algebra Laboratory</td>
       </tr>
       <tr>
        <td align="center">8.</td>
        <td align="center">19AI414</td>
        <td align="center">Fundamentals of web development</td>
       </tr>
       <tr>
        <td align="center">9.</td>
        <td align="center">19AI403</td>
        <td align="center">Introduction to data science</td>
       </tr>
       
        </table>
    
    </table>
</body>
</html>
```

## OUTPUT
![alt text](<Screenshot (60)-1.png>)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
