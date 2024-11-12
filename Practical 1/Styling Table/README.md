Styling Table

This project demonstrates how to display a table with styled content using HTML and CSS. The table displays academic results, including module names, assignments/exams, marks obtained, percentage, and grades.

Features

Styled Table: A simple HTML table with academic data formatted in rows and columns.
Grades: Displays grades based on percentage for each assignment/exam.
Custom Styling: External CSS used to style the table for better presentation and readability.
How to Use

Open the HTML File:
Open the StylingTable.html file in your browser to view the table.
Edit the Table Content:
Modify the content in the HTML table to reflect your own data. You can change the module names, assignments, marks, or percentages.
Customize the Style:
You can edit the external StylingTable.css file to adjust the styling (e.g., background colors, font size, and border styles).




## Code Overview

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Styling Table</title>
    <link rel="stylesheet" href="StylingTable.css">
</head>
<body>
    <Table>
        <tr>
            <th>Module</th> 
            <th>Assignment/ Exam name</th>
            <th>Maximum Marks</th>
            <th>Marks Obtained</th>
            <th>Percentage</th>
            <th>Grade</th>
        </tr>

      
        <tr>
            <td>SDA101</td>
            <td>Figma Design</td>
            <td>10</td>
            <td>7</td>
            <td>70%</td>
            <td>B</td>
        </tr>

        <tr>
            <td>MAT205</td>
            <td>Data Presentation</td>
            <td>10</td>
            <td>8</td>
            <td>80%</td>
            <td>A</td>
        </tr>

        <tr>
            <td>CSF101</td>
            <td>Variables</td>
            <td>10</td>
            <td>7.6</td>
            <td>76%</td>
            <td>B</td>
        </tr>

        <tr>
            <td>DZG101</td>
            <td>Nam aye gay</td>
            <td>10</td>
            <td>6</td>
            <td>60%</td>
            <td>A</td>
        </tr>    
    </Table>
</body>
</html>