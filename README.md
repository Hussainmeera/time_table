# Ex03 Time Table
# Date:28.11.2024
# AIM
To write a html webpage page to display your slot timetable.

# ALGORITHM
## STEP 1
Create a Django-admin Interface.

## STEP 2
Create a static folder and inert HTML code.

## STEP 3
Create a simple table using <table> tag in html.

## STEP 4
Add header row using <th> tag.

## STEP 5
Add your timetable using <td> tag.

## STEP 6
Execute the program using runserver command.

# PROGRAM
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
    <body style="color: rgb(1, 29, 29);">
        <center><table border="3px">
            <tr style="color: black;">
                <th>timing</th>
                <th>8-10</th>
                <th>10-12</th> 
                <td rowspan="7">LUNCH</td>    
                <th>1-3</th>       
                <th>3-5</th>
            </tr>
            <tr>
                <th>MON</th>
                <td></td>
                <td>web</td>
                <td></td>
                <td></td>
            </tr>
            <tr style="font-family: ;">
                <th>TUE</th>
                <td>ENG</td>
                <td></td>
                <td>python</td>
                <td></td>
            </tr>
            <tr>
                <th>WED</th>
                <td>python</td>
                <td>C</td>
                <td></td>
                <td></td>
            </tr>
            <tr>
                <th>THUR</th>
                <td>PHYSICS</td>
                <td>python</td>
                <td>web</td>
                <td></td>
            </tr>
            <tr>
                <th>FRI</th>
                <td>english</td>
                <td>career</td>
                <td>python</td>
                <td></td>
            </tr>
            <tr>
                <th>SAT</th>
                <td></td>
                <td>python</td>
                <td>C</td>
                <td>web</td>
            </tr>
        </table>
    </center>
    </body>
</html>

````
# OUTPUT
![Screenshot 2024-11-28 132537](https://github.com/user-attachments/assets/63b43ffa-2f6f-4a7f-ac79-1942c8ac8d24)


# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
