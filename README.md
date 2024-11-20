# Ex03 Time Table
## Date:19/11/2024

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
<HTML>
    <HEAD>
    <TITLE>Time Table</TITLE>
    </HEAD>
    <BODY>
    <center>
    <img src="/static/logo.png"height="100"width="540">    
    </center>
    <TABLE border = "1" align = "center" cellpadding = "5" bgcolor = "cyan">
    <CAPTION>SLOT TIME TABLE - R HARIRAM (249005836)</CAPTION>
    <TR bgcolor = "yellow">
    <TH>DAY/TIME</TH>
    <TH>8 - 10</TH>
    <TH>10 - 12</TH>
    <TH rowspan = "7">Lunch</TH>
    <TH>1 - 3</TH>
    </TR>
    <TR>
    <TH bgcolor = "yellow">Monday</TH>
    <TD>FREE SLOT</TD>
    <TD>COMMUNICATIVE ENGLISH</TD>
    <TD>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</TD>
    </TD>
    </TR>
    <TR>
    <TH bgcolor = "yellow">Tuesday</TH>
    <TD>ENGINEERING DESIGNING AND MODELLING</TD>
    <TD>DIGITAL ELECTRONICS</TD>
    <TD>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</TD>
    </TR>
    <TR>
    <TH bgcolor = "yellow">Wednesday</TH>
    <TD>ENGINEERING DESIGNING AND MODELLING</TD>
    <TD>PRINCIPLES OF CHEMISTRY IN ENGINEERING</TD>
    <TD>Mentor Meet</TD>
    </TR>
    <TR>
    <TH bgcolor = "yellow">Thursday</TH>
    <TD>COMMUNICATIVE ENGLISH</TD>
    <TD>DIGITAL ELECTRONICS</TD>
    <TD>STATISTICS AND NUMERICAL METHODS</TD>
    </TR>
    <TR>
    <TH bgcolor = "yellow">Friday</TH>
    <TD>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</TD>
    <TD>PRINCIPLES OF CHEMISTRY IN ENGINEERING</TD>
    <TD>STATISTICS AND NUMERICAL METHODS</TD>
    </TR>
    <TR>
    <TH bgcolor = "yellow">Saturday</TH>
    <TD>FREE SLOT</TD>
    <TD>FREE SLOT</TD>
    <TD>FREE SLOT</TD>
    </TR>
    </TABLE>
    <BR>
    <TABLE border = "1" align = "center" cellpadding = "5">
    <CAPTION>Courses</CAPTION>
    <TR>
    <TH>S.No</TH>
    <TH>Course Code</TH>
    <TH>Course Name</TH>
    </TR>
    <TD>1.</TD>
    <TD>19EN101</TD>
    <TD>COMMUNICATIVE ENGLISH</TD>
    </TR>
    <TR>
    <TD>2.</TD>
    <TD>19EY708</TD>
    <TD>Career Development Skills</TD>
    </TR>
    <TR>
    <TD>3.</TD>
    <TD>19EE404</TD>
    <TD>Digital Electronics</TD>
    </TR>
    <TR>
    <TD>4.</TD>
    <TD>19AI302</TD>
    <TD>ENGINEERING DESIGN AND MODELLING</TD>
    </TR>
    <TR>
    <TD>5.</TD>
    <TD>19AI414</TD>
    <TD>Fundamentals Of Web Application</TD>
    </TR>
    <TR>                
    <TD>6.</TD>
    <TD>19CY205</TD>
    <TD>PRINCIPLES OF CHEMISTY IN ENGINEERING</TD>
    </TR>
    </TABLE>
    </BODY>
    </HTML>
    
```


## OUTPUT
Screenshot 2024-11-19 211616.png


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
