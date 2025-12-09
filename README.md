# Ex02 Time Table
## Date:09/12/2025

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
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TIMETABLE</title>
</head>
<body bgcolor="peachpuff">
    <br>
    <center><img src=/static/logo.png height="100" width="700" ></center>
    <hr width="100%" size="5" color="chocolate">
    <center><h1><font color="SaddleBrown">TIMETABLE</font></h1></center>
    <br>
    <table border="5" cellpadding="7" cellspacing="4" align="center" bgcolor="#FFE4B5">
        <tr>
            <th>DAY/TIME</th>
            <th>8-10</th>
            <th>10-12</th>
            <th>12-1</th>
            <th>1-3</th>
            <th>3-5</th>
        </tr>
        <tr>
            <th>MONDAY    </th>
            <td align="center"><font color='purple'>Python      </td>
            <td align="center"><font color='purple'>Python      </td>
            <td rowspan="6" align="center">L<br>U<br>N<br>C<br>H</td>
            <td align="center"><font color='blue'>Web           </td>
            <td align="center"><font color='navy blue'>English  </td>
        </tr>
        <tr>
            <th>TUESDAY    </th>
            <td align="center"><font color='blue'>Web      </td>
            <td align="center"><font color='blue'>Free slot</td>
            <td align="center"><font color='purple'>Python </td>
            <td align="center"><font color='blue'>Web      </td>
        </tr>
        <tr>
            <th>WEDNESDAY  </th>
            <td align="center"><font color='blue'>Web         </td>
            <td align="center"><font color='blue'>Free slot   </td>
            <td align="center"><font color='darkteal'>Mentor  </td>
            <td align="center"><font color='navy blue'>English</td>
        </tr>
        <tr>
            <th>THURSDAY   </th>
            <td align="center"><font color='teal'>Free slot    </td>
            <td align="center"><font color='navy blue'>English </td>
            <td align="center"><font color='blue'>Web          </td>
            <td align="center"><font color='teal'>Free slot    </td>
        </tr>
        <tr>
            <th>FRIDAY     </th>
            <td align="center"><font color='teal'>Free slot  </td>
            <td align="center"><font color='purple'>Python   </td>
            <td align="center"><font color='purple'>Python   </td>
            <td align="center"><font color='teal'>Free slot  </td>
        </tr>
        <tr>
            <th>SATURDAY   </th>
            <td align="center"><font color='teal'>Free slot   </td>
            <td align="center"><font color='teal'>Free slot   </td>
            <td align="center"><font color='teal'>Free slot   </td>
            <td align="center"><font color='navy blue'>English</td>
        </tr>
    </table>
     <br> 
        <table border="5" cellpadding="7" cellspacing="4" align="center" bgcolor='#FFE4B5'>
         <tr>
           <th><h4>S.NO         </h4></th>    
           <th><h4>SUBJECT CODE </h4></th>
           <th><h4>SUBJECT NAME </h4></th>
         </tr>
         <tr>
            <th align="center"><font color='blue'>1.</th>
            <td align="center"><font color='blue'>5P1-2</td>
            <td align="center"><font color='blue'>FUNDAMENDALS OF WEB APPLICATION DEVELOPMENT  </td>
         </tr>
         <tr>
             <th align="center"><font color='navy blue'>2.</th>
             <td align="center"><font color='navy blue'>5P2-1</td>
             <td align="center"><font color='navy blue'>COMMUNICATION ENGLISH  </td>
          </tr> 
          <tr>
             <th align="center"><font color='purple'>>3.</th>
             <td align="center"><font color='purple'>5Q1-1</td>
             <td align="center"><font color='purple'>PYTHON PROGRAMMING  </td>
          </tr> 
          
         </table>   
    </body>
</body>
</html>

## OUTPUT
![alt text](<Screenshot (73).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
