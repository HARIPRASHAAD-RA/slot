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
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
   <style>
   th{ background-color: yellow;}
   td{text-align: center; background-color: aqua;}
</style> 
</head>
<body>
    <img src="WEB_LOGO-01.png" alt="" style=" padding-left: 25%; width: 50%;">

    <h1 style="text-align: center;">SLOT TIME TABLE - HARIPRASHAAD RA (21223040060)</h1> 
    <div style="padding-left: 30%;">
    <table border="1" style=" width: 40%; border-color: aqua; text-align: center;">
    <tr>
        <th>Day/Time</th>
        <th>Monday</th>
        <th>Tuesday</th>
        <th>Wednesday</th>
        <th>Thursday</th>
        <th>Friday</th>
    </tr>
    <tr>
    <td style="background-color: yellow;">8-10</td>
    <td>Physics</td>
    <td>Web</td>
    <td>Chemistry</td>
    <td>Physics</td>
    <td>Free</td>
</tr>
    <tr>
        <td style="background-color: yellow;">10-12</td>
        <td>Maths</td>
        <td>C programming</td>
        <td>Creative Skills</td>
        <td>C programming</td>
        <td>Maths</td>
    </tr>

    <tr>
        <td style="background-color: yellow;">12-1</td>
        <td colspan="5">LUNCH HOUR</td>
        
    </tr>

    <tr>
        <td style="background-color: yellow;" >1-3</td>
        <td>English</td>
        <td>Free</td>
        <td>WEB</td>
        <td>Free</td>
        <td>Chemistry</td>
    </tr>

    <tr>
        <td style="background-color: yellow;">3-5</td>
        <td colspan="4">Free</td>
        
        <td>WEB</td>
    </tr>
    </table>
</div><br>

<div style="margin-left: 31%; margin-right: 25%;">
    <table border="1" style=" width: fit-content; border-color: aqua; text-align: center;">
        <th>S.NO</th>
        <th>Subject code</th>
        <th>Subject Name</th>

        

        <tr>
            <td>1.</td>
            <td>19AI304</td>
            <td>Fundamentals of C programming</td>
            </tr>

            <tr>
                <td>2.</td>
                <td>19AI414</td>
                <td>Fundamentals of Web Application Development</td>
                </tr>

                <tr>
                    <td>3.</td>
                    <td>19CY205</td>
                    <td>Principles of Chemistry in Engineering</td>
                    </tr>


                    <tr>
                        <td>4.</td>
                        <td>19EY702</td>
                        <td>Creative Skills for Communication</td>
                        </tr>


                        <tr>
                            <td>5.</td>
                            <td>19MA201</td>
                            <td>Calculus and Matrix Algebra</td>
                            </tr>

                            <tr>
                                <td>6.</td>
                                <td>19PH204</td>
                                <td>Physics for Quantum Computing</td>
                                </tr>
    </table>




</div>
</body>
</html>
```

## OUTPUT
![Screenshot (78)](https://github.com/HARIPRASHAAD-RA/slot/assets/164654451/5009f420-1bdd-420a-be2f-e3174351b653)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
