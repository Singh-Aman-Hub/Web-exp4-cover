# Ex.06 Book Front Cover Page Design
## Date: 14/05/2025

## AIM:
To design a book front cover page using HTML and CSS.
```
Developed by: Aman Singh
Reg no.212224040020
```
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
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Book Cover</title>
    <style>
        body, html {
            margin: 0;
            padding: 0;
            height: 100%;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            background-color: #eee;
        }

        .book-cover {
            width: 400px;
            height: 600px;
            position: absolute;
            top:5%;
            bottom:5%;
            background-image: url('bg.jpeg'); /* Replace with your background image */
            background-size: cover;
            background-position: center;
            box-shadow: 0 0 20px rgba(0,0,0,0.3);
            border-radius: 10px;
            color: white;
            padding: 40px 30px;
            box-sizing: border-box;
        }

        .book-title {
            font-size: 32px;
            font-weight: bold;
            margin-bottom: 10px;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.6);
        }

        .book-subtitle {
            font-size: 18px;
            font-style: italic;
            margin-bottom: 60px;
            text-shadow: 1px 1px 3px rgba(0,0,0,0.5);
        }

        .author-name {
            position: absolute;
            bottom: 30px;
            left: 20px;
            font-size: 20px;
            font-weight: 600;
            text-shadow: 1px 1px 3px rgba(248, 246, 125, 0.5);
        }
        .edition {
            position: absolute;
            bottom: 50px;
            left: 20px;
            font-size: 20px;
            font-weight: 600;
            text-shadow: 1px 1px 3px rgba(149, 234, 70, 0.5);
        }
           .reg {
            position: absolute;
            bottom: 1px;
            left: 20px;
            font-size: 10px;
            font-weight: 100;
            text-shadow: 1px 1px 3px rgba(0,0,0,0.5);
        }
        
        

        .author-photo {
            position: absolute;
            bottom: 40px;
            right: 20px;
            width: 120px;
            height: 120px;
            border-radius: 50%;
            border: 3px solid #fff;
            background-image: url('author.jpg'); /* Replace with author's photo */
            background-size: cover;
            background-position: center;
            box-shadow: 0 0 10px rgba(0,0,0,0.4);
        }
    </style>
</head>
<body>

    <div class="book-cover">
        <div class="book-title">Responsive Web Design with HTML5 and CSS</div>
        <div class="book-subtitle">Develop all required skills to master web designing. Plus stay ahead with all new added guidance for advanced tool</div>
        <hr>
        <div class="edition">Eighth Edition (updated)</div>
       
        <div class="author-name">By Mr. Aman Singh</div>
         <div class="reg"><h5>Reg no- 212224040020</h5></div>
        <div class="author-photo"></div>
        
    </div>

</body>
</html>


```

## OUTPUT:
![alt text](<Screenshot (1929).png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
