# Ex.06 Book Front Cover Page Design
# Date:29.11.2024
# AIM:
To design a book front cover page using HTML and CSS.

# DESIGN STEPS:
## Step 1:
Create a Django Admin project.

## Step 2:
Create an app in the Django interface.

## Step 3:
Create a folder named 'static' in the app folder.

## Step 4:
Create a new HTML file in the static folder.

## Step 5:
Write the HTML code with relevant CSS properties.

## Step 6:
Choose the appropriate style and color scheme.

## Step 7:
Insert the images in their appropriate places.

## Step 8:
Publish the website in the LocalHost.

# PROGRAM:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Book Cover Page</title>
    <style>
        * {
            margin: 0;
            padding: 0;
        }
        body {
            font-family: 'Arial', sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            border-radius: 40px;
            background-color: #f0f0f0;
            position: relative;
        }
        .book-cover {
            width: 400px;
            height: 600px;
            box-shadow: 0 0 20px rgba(0, 0, 0, 0.3);
            display: flex;
            justify-content: center;
            align-items: center;
            border-radius: 15px;
            position: relative;
            background-image: url(https://i.pinimg.com/enabled_lo/564x/1b/a7/ac/1ba7ac5df19151791432a9cf90fa4be1.jpg);
            background-size: cover;
            background-position: center;
        }
        .top-heading {
            font-size: 1.5em;
            position: absolute;
            left:20px;
            top: 25px;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            font-style: bold;
        }
        .top-line {
            position: absolute;
            top: 10%;
            left: 0;
            width: 45%;
            height: 2px;
            background-color: white;
        }
        .cover-content {
            text-align: center;
        }
        .title {
            font-size: 3.5em;
            font-weight: bold;
            margin-bottom: 10px;
            font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
        }
        .subtitle {
            font-size: 1.5em;
            margin-bottom: 50px;
            font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
        }
        .bottom-heading {
            font-size: 2em;
            position: absolute;
            left:20px;
            bottom: 100px;
            text-decoration: underline;
        }
        .author {
            font-size: 1.5em;
            position: absolute;
            bottom: 50px;
            right: 20px;
            font-style: italic;
        }
        .bottom-line{
            position: absolute;
            bottom: 15%;
            left: 0;
            width: 100%;
            height: 2px;
            background-color: white;
        }
        .pic{
            position: relative;
            top: 70px;
            left:280px;
            width: 100px;
            height: 100px;
            background-size: cover;
            border:1px black;
            box-sizing: border-box;
        }
    </style>
</head>
<body>
    <div class="book-cover">
        <div class="top-line"></div>
        <div class="top-heading"><b>mastering life</b></div>
        <div class="bottom-line"></div>
        <div class="bottom-heading">First edition</div>
        <div class="cover-content">
            <h1 class="title">World of Maze</h1>
            <h2 class="subtitle"><i>Unlocking the ways of life</h2></i>
            <div class="pic">
                <img src="C:\Users\admin\Pictures\Screenshots\Screenshot 2024-12-05 153558.png" width="100" height="100">
            </div>
            <p class="author">by John Doe</p>
        </div>
</body>
</html>
```
# OUTPUT:
![alt text](<Screenshot 2024-12-06 023947.png>)

# RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
