## College Events

This project presents a simple HTML structure for listing various college events, including concerts, academic sessions, campus cleaning, and prayer sessions. The events are organized with ordered and unordered lists to provide a clear and structured overview.

# Features

Event Categories: Includes different event types such as concerts, academic events, cleaning drives, and prayer sessions.
Event Details: Sub-events are listed with specific information like venue and time.
External Styling: The form is linked to an external CSS file for styling.
How to Use

Open the HTML File:
Open the file in a web browser to view the list of events.
Modify Event Details:
Edit the HTML to add, remove, or update events and their details.
Style the Page:
Use the linked Exercise style.css file to customize the look and feel of the events list.


## Code Overview

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>College EVES</title>
    <h1> College Events</h1> <br>
    <link rel="stylesheet" href="Exercise style.css">

</head>
<body>

    <div>
        <ol>
            <li>Concert</li>
        <ul>
           <li>Welcome Show</li>
           <li>LT Hall</li>
           <li>6:30 pm</li> <br><br>
        </ul>

           <li>Academic Events</li>
        <ul>
           <li>Health Talk</li>
           <li>Audiotorium</li>
           <li>8:30 am</li> <br><br>
        </ul>

            <li>Cleaning Campus</li>

        <ul>
           <li>Mass Cleaning</li>
           <li>Campus</li>
           <li>1:30 pm</li> <br><br>
        </ul>
           <li>Pray</li>
        <ul>
           <li>Mass Cleaning</li>
           <li>Campus</li>
           <li>1:30 pm</li> <br><br>
        </ul>

    </ol>
    </div>

    </div>
</body>
</html>