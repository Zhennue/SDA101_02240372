## Sample Landing Page

This project features a simple landing page layout, with navigation buttons that link to different pages like Home, Products, About Us, and Contact. The page is styled with CSS to center the content and give it a visually appealing, structured design.

# Features

Navigation Buttons: Links to different sections of the site (Home, Products, About Us, and Contact).
Centered Layout: The content is centered both horizontally and vertically within the viewport using CSS Grid.
Styling: External and internal CSS used for styling the page, including font and background colors.
Responsive Image: An image is displayed and centered on the page using CSS.
How to Use

Open the HTML File:
Open SimpleLandingPage.html in your browser to view the landing page.
Modify the Content:
Edit the HTML content to change the name, links, or add more sections as needed.
Style the Page:
Customize the SimpleLandingPage.css file to enhance the appearance of the page, adjust colors, fonts, or layout.



## Code Overview

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sample Landing Page</title>
    <link rel="stylesheet" href="SimpleLandingPage.css">
    <style>
        h1{
            font-family: 'Courier New', Courier, monospace;
        }

        h4{
            font-family: Georgia, 'Times New Roman', Times, serif;
        }
    </style>

    <style>
        body{
            height: 100vh;
            width: 100vw;
            background-color: gray;
            display: grid;
            place-items: center;
        }

        .box{
            height: 680px;
            width: 715px;
            border: 2px solid pink;
            background-color: aqua;
        }
    </style>

    <style>
        .CenterImage{
            display: block;
            margin-left: auto;
            margin-right: auto;
        }
    </style>
</head>

<body>

    <link rel="stylesheet" href="SimpleLandingPage.css">

    <div class="container">

       

        <div class="box">

            <header>
                <h1 align="center">ZALA.BT</h1>
            </header>

            <button1 align="center">
                <a href="SimpleLandingPage.html">HOME</a><br>            
            </button1>

            <button2>
                <a href="Products.html">PRODUCTS</a> 
            </button2>

            <button3>
                <a href="AboutUs.html">ABOUT US</a>
            </button3>

            <button4>
                <a href="Contact.html">CONTACT</a>
            </button4>

             <img src="image.png" class="CenterImage">
             
        </div>
        
        
    </div>

</body>
</html>
