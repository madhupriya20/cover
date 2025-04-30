# Ex.06 Book Front Cover Page Design
## Name:Madhupriya R
## Reg No:212224040177
## Date: 30-04-2025

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
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Book Cover</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            background-color: #f0f0f0;
        }

        .background-container {
            width: 210mm;
            height: 297mm;
            background-color: #fff;
            background-image: url('back.jpg');
            background-repeat: no-repeat;
            background-position: center;
            background-size: cover;
            position: relative;
            padding: 20px;
            border: 2px solid #333;
        }

        .text-container {
            position: absolute;
            top: 5%; 
            left: 5%;
            color: #333;
            z-index: 10;
            font-size: 18px;
            line-height: 1.4;
            width: 60%; 
        }

        .expert-insight {
            font-size: 24px;
            font-weight: bold;
            color: #333;
            font-family: 'Georgia', serif;
            margin-bottom: 10px;
        }

        .book-title {
            font-size: 30px;
            font-weight: bold;
            line-height: 1.3;
        }

        .subtitle {
            font-size: 20px;
            font-style: italic;
            font-weight: 300;
            color: #6a6a6a;
            margin-top: 10px;
        }

        .author-name {
            font-size: 22px;
            font-weight: 300;
        }

        .line {
            width: 50%; 
            border-top: 3px solid #000; 
            margin-top: 10px;
        }

        .image-container {
            position: absolute;
            bottom: 12%;
            right: 5%;
        }

        .image-container img {
            width: 130px;
            height: 130px;
            border-radius: 5px;
            object-fit: cover;
        }

    </style>
</head>
<body>

<div class="background-container">
    <div class="text-container">
        <div class="expert-insight">
            Self-Help
        </div>
        <div class="line"></div> 
        <div class="book-title">
            "Unfolding You: A Journey Inward"
        </div>
        <div class="author-name">Madhupriya R</div>
    </div>

    <div class="image-container">
        <img src="myphoto.jpg" alt="Your Image">
    </div>
</div>

</body>
</html>
```


## OUTPUT:
<img width="960" alt="2025-04-30 (2)" src="https://github.com/user-attachments/assets/099a9774-fb18-4f60-bb07-76b01e85b19b" />


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
