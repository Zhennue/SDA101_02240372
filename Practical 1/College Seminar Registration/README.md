## College Seminar Registration Form

This project features a simple HTML form designed for registering participants for a college seminar. The form collects basic personal and seminar-related information such as name, date of birth, gender, contact details, and meal preferences.

# Features

Name: Text input for the participant's name.
Date of Birth: Date picker for selecting the participant's birth date.
Gender: Radio buttons for choosing gender (Male, Female, or Others).
Email and Password: Fields for entering email and password.
Phone Number: Text input for providing a contact number.
Preferred Seminar Time: Time picker to select a preferred seminar time.
Meal Preference: Radio buttons for choosing a meal type (Vegetarian, Non-Vegetarian, or Vegan).
Submit Button: A button to submit the form (currently non-functional).
How to Use

Open the HTML file:
Double-click the file or open it in your web browser to access the form.
Fill in the fields:
Complete the form with valid information. Select the appropriate options for radio buttons and pick the correct date and time.
Enhance Functionality:
The form can be further developed with JavaScript to validate input, process data, and submit it to a backend server.



## Code Overview

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>College seminar Registration</title>
</head>
<body>
    <label for="Name">Name:</label>
    <input type="text"> <br><br><br>
    
    <label for="Date of Birth">Date of Birth:</label>
    <input type="date"><br><br><br>

    <label for="Gender">Gender:</label><br><br>
    <label for="Male">Male</label>
    <input type="radio" name="Gender">
    <label for="Female">Female</label>
    <input type="radio" name="Gender">
    <label for="Other">Others</label>
    <input type="radio" name="Gender"> <br><br><br>

    <label for="Email">Email Adress:</label>
    <input type="text"> <br><br>
    <label for="Password">Password:</label>
    <input type="text"> <br><br><br>

    <label for="Phone Number">Phone Number:</label>
    <input type="text"><br><br><br>

    <label for="PST">Preferred Seminar Time:</label>
    <input type="time"><br><br><br>

    <label for="MP">Meal Preference:</label> <br><br>
    <label for="Veg">Vegeterian</label>
    <input type="radio" name="Meal Preference">
    <label for="Non-Veg">Non-Vegeterian</label>
    <input type="radio" name="Meal Preference">
    <label for="Vegan">Vegan</label>
    <input type="radio" name="Meal Preference"> <br><br><br><br><br>

    <label for="Submit Button">Submit </label>
    <input type="button">

</body>
</html>