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
```
<html>
    <head>
        <title>My time table</title>
    </head>
    <body>
       <center> <img   src="logo.png" height="=200" width="500"> </center>
        <hr>
        <hr>
        <table align="center" border="2" cellspacing="5" cellpadding="12" height="50" width="40" >
            <center><h3><b>TIME TABLE</b></h3></center>
            <center><h4>VIGNESH V 212223110062</h4></center>
            <tr>
             <th bgcolor="EEE4B1">Day/time</th>
             <th bgcolor="FFEDD8">Monday</th>
             <th bgcolor="FFEDD8">Tuesday</th>
             <th bgcolor="FFEDD8">Wednesday</th>
             <th bgcolor="FFEDD8">Thursday</th>
             <th bgcolor="FFEDD8">Friday</th>
             <th bgcolor="FFEDD8">Saturday</th>
            </tr>
            <tr>
                <td  bgcolor="EEE4B1">8-10</td>
                <td bgcolor="67C6E3">digital electroincs</td>
                <td bgcolor="67C6E3">free slot</td>
                <td bgcolor="67C6E3">theory of computation</td>
                <td bgcolor="67C6E3">statistics</td>
                <td bgcolor="67C6E3">web application</td>
                <td bgcolor="67C6E3">free slot</td>
            </tr>
            <tr>
                <td  bgcolor="EEE4B1">10-12</td>
                <td bgcolor="67C6E3">free slot</td>
                <td bgcolor="67C6E3">c programing</td>
                <td bgcolor="67C6E3">Free slot</td>
                <td bgcolor="67C6E3" align="centre">c programing</td>
                <td bgcolor="67C6E3">computer networks</td>
                <td bgcolor="67C6E3">theory of computation</td>
            </tr>
            <tr>
                <td  bgcolor="EEE4B1">12-1</td>
                <td colspan="6" align="center">LUNCH</td>
            </tr>
            <tr>
                <td  bgcolor="EEE4B1">1-3</td>
                <td bgcolor="67C6E3">computer networks</td>
                <td bgcolor="67C6E3">web application</td>
                <td bgcolor="67C6E3" rowspan="2">free solt</td>
                <td bgcolor="67C6E3">Web application</td>
                <td bgcolor="67C6E3" rowspan="2">free slot</td>
                <td bgcolor="67C6E3"> statistics</td>
            </tr>
            <tr>
                <td bgcolor="EEE4B1">3-5</td>
                <td bgcolor="67C6E3">free slot</td>
                <td bgcolor="67C6E3">free slot</td>
                <td bgcolor="67C6E3">digital electroincs</td>
                <td bgcolor="67C6E3">free slot</td>
            </tr>
        </table>
        <hr>
        <hr>
        <table align="center" border="2" cellspacing="1" cellpadding="12" height="50" width="600">
            <tr>
                <th>S.NO</th>
                <th>Subject Code</th>
                <th>Subject Name</th>
            </tr>
            <tr>
                <td>1.</td>
                <td align="center">19AI414</td>
                <td >Fundamentals of Web Application Development</td>
            </tr>
            <tr>
                <td>2.</td>
                <td align="center">19CS406</td>
                <td>Computer Networks</td>
            </tr>
            <tr>
                <td>3.</td>
                <td align="center">19AI304</td>
                <td>Fundamentals of c programming</td>
            </tr>
            <tr>
                <td>4.</td>
                <td align="center">19CS407</td>
                <td>Theory of Computation</td>
            </tr>
            <tr>
                <td>5.</td>
                <td>19EE404</td>
                <td>Digital electroincs</td>
            </tr>
            <tr>
                <td>6.</td>
                <td>19MA211</td>
                <td>Statistics and Numerical Methods</td>
            </tr>
        </table>
    </body>
</html>
```


## OUTPUT
![image](https://github.com/Vigneshv-23/slot/assets/110780412/776533b2-e583-42ea-80d5-9d26591e6a17)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
