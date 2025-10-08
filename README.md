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
    <html lang="en">
    <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Book Cover: Fundamentals of Web Application Development</title>
    <link rel="stylesheet" href="style.css">
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css">
    <style>
    *  {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
        }

    body {'

    background-color: #f4f4f9; 
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
    font-family: 'Montserrat', sans-serif; /* Use the sleek Google Font */
     }
   
    .book-cover {
    /* Standard book size ratio (e.g., 6x9 inches) for display */
    width: 300px;
    height: 450px; 
    
    /* Dark, sleek background with a subtle gradient */
    background: linear-gradient(135deg, #1e1e3f, #0d0d2b); 
    
    color: #ffffff;
    padding: 30px;
    
    /* Layout using Flexbox for easy positioning */
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    
    /* Optional: Subtle box-shadow for a physical feel */
    box-shadow: 0 10px 30px rgba(0, 0, 0, 0.5);
    border-radius: 5px;
    }


 
    .header {
    display: flex;
    flex-direction: row;
    gap: 40px;
    justify-content: center; 
    align-items: center;/* Push the icon to the top right */
     }

    .book-icon {
    font-size: 2.5em;
    /* Use a vibrant color for a modern look */
    color: #4CAF50; /* A tech-focused green */
    opacity: 0.8;
     }

 
    .title-section {
    text-align: center;
    display: flex;
    flex-direction: column;
    justify-content: center;
    padding: 10px; 
     }

     .main-title {
    font-size: 1.8em;
    font-weight: 700;
    line-height: 1.2;
    margin-bottom: 15px;
    /* Use a slightly off-white for better contrast on dark backgrounds */
    color: #e0e0e0; 
    text-transform: uppercase;
    letter-spacing: 1px;
    align-items: center;
    margin-right: 15px;
     }

    .sub-title {
    font-size: 0.85em;
    font-weight: 400;
    line-height: 1.5;
    color: #90a4ae; /* A light grey for the subtitle */
    text-transform: uppercase;
    letter-spacing: 0.5px;
     }

 
    .footer {
    display: flex;
    justify-content: space-between;
    align-items: flex-end;
    font-size: 0.65em;
    text-transform: uppercase;
    color: #90a4ae;
     }

    .author {
    font-weight: 700;
    letter-spacing: 1px;
     }
    .publisher {
    font-weight: 400;
    letter-spacing: 0.5px;
    }
    </style>
     </head>
    <body>
    <div class="book-cover">
        <div class="header">
            <h3 style="text-decoration: underline;">SEC INSIGHTS</h3>     
        </div>
        <div class="title-section">
            <h1 class="main-title">FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</h1>
            <h2 class="sub-title">DEEP DIVE INTO HTML AND CSS & JS BASICS</h2>
        </div>
        <div class="footer">
            <div class="author">
                SAIRAM
            </div>
        </div>
    </div>
    </body>
    </html>


## OUTPUT:
<img width="404" height="608" alt="image" src="https://github.com/user-attachments/assets/17bf2b75-d010-43e7-be62-d01fefb6c953" />



## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
