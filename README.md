# Ex.06 Book Front Cover Page Design
## Date:

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

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Book Front Page</title>
  <style>
    body, html {
      margin: 0;
      padding: 0;
      height: 100%;
      font-family: 'Georgia', serif;
    }

    .front-page {
      background-image: url('OKK.jpg'); /* Replace with your background image */
      background-size: cover;
      background-position: center;
      height: 100%;
      color: white;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      text-align: center;
      padding: 20px;
    }

    .book-title {
      font-size: 3em;
      font-weight: bold;
      margin-bottom: 10px;
      text-shadow: 2px 2px 4px #000;
    }

    .subtitle {
      font-size: 1.5em;
      font-style: italic;
      margin-bottom: 30px;
      text-shadow: 1px 1px 3px #000;
    }

    .author-image {
      width: 150px;
      height: 150px;
      border-radius: 50%;
      border: 4px solid white;
      object-fit: cover;
      margin-bottom: 20px;
      box-shadow: 0 0 10px rgba(0,0,0,0.6);
    }

    .author-name {
      font-size: 1.2em;
      font-weight: 500;
      text-shadow: 1px 1px 3px #000;
    }
  </style>
</head>
<body>
  <div class="front-page">
    <img src="msd.jpg" alt="Author Image" class="author-image"> <!-- Replace with your author image -->
    <div class="book-title">JOURNEY OF MS DHONI</div>
    <div class="subtitle">LEGEND</div>
    <div class="author-name">by AANANDHA KANNAN.S</div> <!-- Replace "Your Name" with your actual name -->
  </div>
</body>
</html>

## OUTPUT:

![Screenshot 2025-04-28 140218](https://github.com/user-attachments/assets/4bd7acf7-ffbe-43fa-8ffa-28f5507ac255)



## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
