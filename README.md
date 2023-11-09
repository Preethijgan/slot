# Ex03 Time Table
## Date:
09/11/2023

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
<title> Time Table </title>
</head>

<body>

<center>
<img src="/static/logo.png" height="100" width="540">
</center>
<br>

<table align="center" width="800" cellspacing="3" cellpadding="14" border="2" bgcolor="blue">
<caption> <b> SLOT TIME TABLE - Preethi J (23008364) </b> </caption>

<tr align="center">
<th bgcolor="cyan"> Day / Time </th>
<th bgcolor="cyan"> 8 - 10 </th>
<th bgcolor="cyan"> 10 - 12 </th>
<th bgcolor="cyan"> 12 - 1 </th>
<th bgcolor="cyan"> 1 - 3 </th>
<th bgcolor="cyan"> 3 - 5 </th>
</th>

<tr align="center">
<th bgcolor="cyan"> Monday </th>
<td bgcolor="white">Basic Electrical,Electronics and Measurement Engineering </td>
<td bgcolor="white">Free Slot</td>
<td rowspan="5" bgcolor="white"> Lunch </td>
<td bgcolor="white"> Engineering Design and Modelling</td>
<td bgcolor="white"> Digital Electronics</td>
</tr>

<tr align="center">
<th bgcolor="cyan"> Tuesday </th>
<td colspan="2" bgcolor="white">Free Slot</td>
<td bgcolor="white"> Free Slot</td>
<td bgcolor="white"> Soft Skill </td>
</tr>

<tr align="center">
<th bgcolor="cyan"> Wednesday </th>
<td bgcolor="white"> Fundamentals of Web Application Development </td>
<td bgcolor="white"> Python Programming </td>
<td colspan="2" bgcolor="white">Free Slot </td>
</tr>

<tr align="center">
<th bgcolor="cyan"> Thursday </th>
<td bgcolor="white"> Engineering Design And Modelling </td>
<td bgcolor="white"> Fundamentals of Web Application Development </td>
<td bgcolor="white"> Python Programming </td>
<td bgcolor="white"> Calculus And MAtrix Algebra </td>
</tr>

<tr align="center">
<th bgcolor="cyan"> Friday </th>
<td bgcolor="white"> Calculus And Matrix Algebra </td>
<td bgcolor="white"> Basic Electrical, Electronics and Measurement Engineering </td>
<td bgcolor="white"> Fundamentals of Web Application Development </td>
<td bgcolor="white"> Digital Electronics </td>
</tr>
</table>
<br>
<br>

<table align="center" cellspacing="3" cellpadding="15" border="2" bgcolor="blue">

<tr align="center">
<th bgcolor="cyan"> S.No. </th>
<th bgcolor="cyan"> Subject Code </th>
<th bgcolor="cyan"> Subject Name </th>
</tr>

<tr>
<th align="center" bgcolor="white"> 1. </th>
<td align="center" bgcolor="white"> 19AI414 </td>
<td bgcolor="white"> Fundamentals of Web Application Development </td>
</tr>

<tr>
<th align="center" bgcolor="white"> 2. </th>
<td align="center" bgcolor="white"> 19AI301 </td>
<td bgcolor="white">Python Programming  </td>
</tr>

<tr>
<th align="center" bgcolor="white"> 3. </th>
<td align="center" bgcolor="white"> 19AI302</td>
<td bgcolor="white"> Engineering Design and Modelling </td>
</tr>

<tr>
<th align="center" bgcolor="white"> 4. </th>
<td align="center" bgcolor="white"> 19MA201 </td>
<td bgcolor="white"> Calculus and Matrix Algebra </td>
</tr>

<tr>
<th align="center" bgcolor="white"> 5. </th>
<td align="center" bgcolor="white"> 19EE305 </td>
<td bgcolor="white"> Basic Electricals, Electronics and Measurement Engineering </td>
</tr>

<tr>
<th align="center" bgcolor="white"> 6. </th>
<td align="center" bgcolor="white"> 19EY701 </td>
<td bgcolor="white"> Soft Skill </td>
</tr>

<tr>
<th align="center" bgcolor="white"> 6. </th>
<td align="center" bgcolor="white"> 19EE404 </td>
<td bgcolor="white"> Digital Electronics </td>
</tr>

</body>
</html>

```
## OUTPUT


![Alt text](<Screenshot 2023-11-09 143758.png>)
![Alt text](<Screenshot 2023-11-09 143812.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully