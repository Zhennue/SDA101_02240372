## Student Information Form

This project features an HTML form to collect basic student information. The form includes radio buttons to select the class and a text input to enter the student ID.

# Features

Class Selection: The user can choose between three classes (10, 11, or 12) using radio buttons.
Student ID Input: A text input field to enter the student's ID.
How to Use

Open the HTML File:
Open the Document.html file in your browser to view the form.
Select Class:
Choose one of the available classes (10, 11, or 12) using the radio buttons.
Enter Student ID:
Fill in the student ID by typing it into the text input field.
Submit the Form:
This HTML form currently lacks a submit button or processing functionality. You can add a submit button and backend logic to handle form submission.




## Code

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    
    <label for="class">Class:</label> <br><br>
    <label for="10">10</label>
    <input type="radio" name="Class">
    <label for="11">11</label>
    <input type="radio" name="Class">
    <label for="12">12</label>
    <input type="radio" name="Class"> <br><br>

    <label for="Student ID">:Student ID</label>
    <input type="text" name="Student ID">

</body>
</html>