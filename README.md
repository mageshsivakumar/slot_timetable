# Ex03 Time Table
## Date: 25/04/2025
## Name : Magesh S
## Reg no : 212224040180
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
<!DOCTYPE html><html>
<head>
    <title>Class Timetable</title>
    <style>
        table {
            width: 60%;
            border-collapse: collapse;
            margin-bottom: 20px;
        }
        th, td {
            border: 1px solid black;
            padding: 8px;
            text-align: center;
        }
        th {
            background-color:red;
        }
        .highlight {
            background-color:yellow;
        }
    </style>
</head>
<body>
<center>
    <img src="new.jpeg" alt="nope" height="151" width="700"></center>

    
<h2>Class Timetable</h2>
<table>
    <tr>
        <th>Day/Time</th>
        <th>Monday</th>
        <th>Tuesday</th>
        <th>Wednesday</th>
        <th>Thursday</th>
        <th>Friday</th>
        <th>Saturday</th>



    </tr>
    <tr class="highlight">
        <td>8-10</td>
        <td>FREE</td>
        <td>FREE</td>
        <td>FREE</td>
        <td>FREE</td>
        <td>FREE</td>
        <td>FREE</td>
    </tr>
    <tr class="highlight">
        <td>10-12</td>
        <td>BEEE</td>
        <td>CA</td>
        <td>FUNDS OF C</td>
        <td>COMMUNICATIVE ENGLISH</td>
        <td>FREE</td>
        <td>FREE</td>

    </tr>
    <tr>
        <td>12-1</td>
        <td colspan="5">LUNCH</td>
    </tr>
    <tr class="highlight">
        <td>1-3</td>
        <td>OMMUNICATIVE ENGLISH</td>
        <td>WEB</td>
        <td>MENTOR</td>
        <td>PROBABILITY</td>
        <td>WEB</td>
        <td>FUNDS OF C</td>
    </tr>
    <tr class="highlight">
        <td>3-5</td>
        <td>FREE SLOT</td>
        <td>FREE</td>
        <td>CA</td>
        <td>FREE</td>
        <td>BEEE</td>
        <td>PROBABILITY</td>
    </tr>
</table>

<h2>Subject Details</h2>
<table>
    <tr>
        <th>S. No.</th>
        <th>Subject Code</th>
        <th>Subject Name</th>
    </tr>
    <tr>
        <td>1</td>
        <td>19AI414</td>
        <td>Fundamentals of Web Application Development (FWAD)</td>
    </tr>
    <tr>
        <td>2</td>
        <td>19AI304</td>
        <td>FUNDS OF C</td>
    </tr>
    <tr>
        <td>3</td>
        <td>19CS305</td>
        <td>COMPUTER ARCHITECTURE</td>
    </tr>
    <tr>
        <td>4</td>
        <td>19EE305</td>
        <td>BEEE</td>
    </tr>
    <tr>
        <td>5</td>
        <td>19EN101</td>
        <td>COMMUNICATIVE ENGLISH</td>
    </tr>
    
    <tr>
        <td>7</td>
        <td>19MA222</td>
        <td>PROBABILITY</td>
    </tr>

</table>
</center>

</body>
</html>

```
## OUTPUT
![Screenshot 2025-04-25 133754](https://github.com/user-attachments/assets/81751db6-cb76-4aaf-8495-190e1c7bbcf2)



## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
