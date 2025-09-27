# Ex03 Time Table
## Date:23/9/2025

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
    <img src="/static/logo.png" height="100" width="540"
</center>
<br>
<table align="center" width="540" cellspaceing="2" cellpading="4" border="5" bgcolour="cyan">
<caption><b>SLOT TIMETABLE - PRANAY N (2501770)</b></caption>
<tr align="center">
<th bgcolor="yellow">Day/Time</th>
<th bgcolor="yellow">Monday</th>
<th bgcolor="yellow">Tuesday</th>
<th bgcolor="yellow">Wednesday</th>
<th bgcolor="yellow">Thursday</th>
<th bgcolor="yellow">friday</th>
<th bgcolor="yellow">saturday</th>
</tr>
<tr align="center">
<th bgcolour="yellow">8-10</th>
<td>FUNDAMENTALS OF WEB APPLICATION</td>
<td>FUNDAMENTALS OF WEB APPLICATION</td>
<td>COMMUNICATIVE ENGLISH</td>
<td>FREE</td>
<td>FUNDAMENTALS OF WEB APPLICATION</td>
<td>free</td>
</tr>
<tr align="center">
<th bgcolor="yellow">10-12</th>
<td>PYTHON PROGRAMMING</td>
<td>COMMUNICATIVE ENGLISH</td>
<td>COMMUNICATIVE ENGLISH</td>
<td>PYTHON PROGRAMMING</td>
<td>COMMUNICATIVE ENGLISH</td>
<td>COMMUNICATIVE ENGLISH</td>
</tr>
<tr align="center">
<th bgcolor="yellow">1-3</th>
<td>FUNDAMENTALS OF WEB APPLICATION</td>
<td>FUNDAMENTALS OF WEB APPLICATION</td>
<td>MENTOR MEET</td>
<td>FREE</td>
<td>COMMUNICATIVE ENGLISH</td>
<td>FREE</td>
</tr>
<tr align="center">
<th bgcolor="yellow">3-5</th>
<td>FREE</td>
<td>FREE</td>
<td>PYTHON PROGRAMMING</td>
<td>PYTHON PROGRAMMING</td>
<td>PYTHON PROGRAMMING</td>
<td>FREE</td>
</tr>
</table>
<br>
<table align="center" cellspacing="2" cellpadding="4" border="2">
<tr align="center">
<th>s.no</th>
<th>subject code</th>
<th>subject name</th>
</tr>
<tr>
<td align="center">1.</td>
<td align="center">19AI414</td>
<td>FUNDAMENTALS OF WEB APPLICATION</td>
</tr>
<tr>
<td align="center">2.</td>
<td align="center">19AI303</td>
<td>PYTHON PROGRAMMING</td>
</tr>
<tr>
<td align="center">3.</td>
<td align="center">ENGLISH</td>
<td>COMMUNICATIVE ENGLISH</td>
</tr>
</table>
</body>
</html>

```
## OUTPUT
![alt text](<Screenshot (15).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
