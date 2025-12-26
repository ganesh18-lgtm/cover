# Ex.06 Book Front Cover Page Design
## Date:10/12/2025
## Ref No:25013050
## AIM:
To design a book front cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Create a Django Admin project.

### Step 2:
Create an app in the Django interface.

### Step 3:
Create a folder named 'static' in the app folder.

### Step 4:
Create a new HTML file in the static folder.

### Step 5:
Write the HTML code with relevant CSS properties.

### Step 6:
Choose the appropriate style and color scheme.

### Step 7:
Insert the images in their appropriate places.

### Step 8:
Publish the website in the LocalHost.

## PROGRAM:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>ganesh(25013050)</title>
    <title>Harry Potter Book Cover</title>
    <style>
        body {
            background: #111;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            font-family: 'Georgia', serif;
        }

        .book-cover {
            width: 350px;
            height: 500px;
            background: linear-gradient(135deg, #2b1055, #000428);
            border-radius: 12px;
            box-shadow: 0 20px 40px rgba(0,0,0,0.7);
            color: gold;
            text-align: center;
            padding: 30px 20px;
            position: relative;
            overflow: hidden;
        }

        .book-cover::before {
            content: "";
            position: absolute;
            inset: 0;
            background: url('https://www.transparenttextures.com/patterns/stardust.png');
            opacity: 0.3;
        }

        .title {
            font-size: 32px;
            font-weight: bold;
            letter-spacing: 2px;
            margin-top: 40px;
            text-transform: uppercase;
            position: relative;
            z-index: 1;
        }

        .subtitle {
            font-size: 22px;
            margin-top: 20px;
            font-style: italic;
            position: relative;
            z-index: 1;
        }

        .symbol {
            font-size: 80px;
            margin: 40px 0;
            position: relative;
            z-index: 1;
        }

        .author {
            font-size: 18px;
            position: absolute;
            bottom: 30px;
            width: 100%;
            left: 0;
            text-align: center;
            letter-spacing: 1px;
            z-index: 1;
        }

        .border {
            position: absolute;
            inset: 15px;
            border: 2px solid gold;
            border-radius: 8px;
            z-index: 1;
        }
    </style>
</head>
<body>

<div class="book-cover">
    <div class="border"></div>
    <div class="title">Fundamentals of Web application</div>
    <div class="subtitle">book cover</div>
    <div class="symbol">📚</div>
    <div class="author">Ganesh B C (25013050)</div>
</div>
</body>
</html>


```

## OUTPUT:
![alt text](<Screenshot 2025-12-20 014456.png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
