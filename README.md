# Ex03 Time Table

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

## CODE
```
<!DOCTYPE html>
<html lang="en">
<head>
<title>Slot Timetable</title>
</head>
<body>
<center>
<img src="/static/images/logo.png" height=120" width="1150">
</center>
<br>
<table align="center" width="540" cellspacing="2" cellpadding="4" border="5" bgcolor="cyan">
<caption><b>SLOT TIME TABLE - SUBALAKSHMI.S(212222100051)</b></caption>
<tr align="center">
<th bgcolor="yellow">Day/Time</th>
<th bgcolor="yellow">Monday</th>
<th bgcolor="yellow">Tuesday</th>
<th bgcolor="yellow">Wednesday</th>
<th bgcolor="yellow">Thursday</th>
<th bgcolor="yellow">Friday</th>
</tr>
<tr align="center">
<th bgcolor="yellow">8-10</th>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
<td>WEB</td>
<td>WEB</td>
</tr>
<tr align="center">
<th bgcolor="yellow">10-12</th>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
<td>PROBABILITY</td>
<td>PROBABILITY</td>
<td>FREE SLOT</td>
</tr>
<tr>
<th bgcolor="yellow">12-1</th>
<td colspan="5" align="center">L U N C H</td>
</tr>
<tr align="center">
<th bgcolor="yellow">1-3</th>
<td>ADVANCE C PROGRAM</td>
<td>FREE SLOT</td>
<td>WEB</td>
<td>FREE SLOT</td>
<td>COMPUTER NETWORKS</td>
</tr>
<tr align="center">
<th bgcolor="yellow">3-5</th>
<td>FREE SLOT</td>
<td>ADVANCE C PROGRAM</td>
<td>COMPUTER NETWORKS</td>
<td>FREE SLOT</td>
<td>CREATIVE SKILLS</td>
</tr>
</table>
<br>
<table align="center" cellspacing="2" cellpadding="4" border="2">
<tr align="center">
<th>S. No.</th>
<th>Subject Code</th>
<th>Subject Name</th>
</tr>
<tr>
<td align="center">1.</td>
<td align="center">19AI414</td>
<td>Fundamentals of Web Application Development (WEB)</td>
</tr>
<tr>
<td align="center">2.</td>
<td align="center">19AI305</td>
<td>ADVANCE C PROGRAM</td>
</tr>
<tr>
<td align="center">3.</td>
<td align="center">19CS406</td>
<td>COMPUTER NETWORKS</td>
</tr>
<tr>
<td align="center">4.</td>
<td align="center">19EY702</td>
<td>CREATIVE SKILLS FOR COMMUNICATION</td>
</tr>
<tr>
<td align="center">5.</td>
<td align="center"> 19MA222</td>
<td>PROBABILITY AND QUEUEING MODELS</td>
</tr>

</table>
</body>
</html>
```



## OUTPUT
![out3](https://user-images.githubusercontent.com/121957896/233535524-dab97518-2541-437f-9a63-4acd6e91bdf9.png)



## HTML VALIDATOR
![valid](https://user-images.githubusercontent.com/121957896/233535556-f3ddab78-d36f-4b14-8e81-f991c4a72ff0.png)



## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
