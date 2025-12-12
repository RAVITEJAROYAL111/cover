# Ex.05 Book Cover Page Design
## Date:11-12-2025

## AIM:
To design a book back cover page using HTML and CSS.

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
cover.html
<html>
    <head>
        <title>flexbox</title>
         <link rel="stylesheet" href="style.css">
    </head>
    <body>
       
        <div class="container">
            <h1>ABOUT THE BOOK</h1>
            <hr></hr>
            <P>
               “The C Programming Language” by Brian W. Kernighan and Dennis Ritchie is one of the most influential technology books in computer science. It introduces the C language, which is the foundation for many modern technologies, operating systems, and programming languages (like C++, Java, Python interpreters, and more).
            </P>
        </div>
        <div class="items">
            <p>
             “The C Programming Language is a timeless guide that shaped the way modern programming is taught.”
            </p>
        </div>
        <div class="author">
            <img src="1.jpg" alt="Author" class="profile-img">
            
            <div>
                <h2>R SIVA</h2>
                <p>
                Siva is a dedicated student pursuing Cybersecurity at Saveetha College. He is interested in modern security technologies and enjoys learning how to protect systems, networks, and data from digital threats. With a strong passion for technology and problem-solving, Siva aims to build a successful career in the cybersecurity field.
                </p>
            </div>
        </div>

        <div class="footer">
            <span class="publish"> World viewer, Publishers</span>
            <span class="price">Price: ₹499</span>
            <br>
            <span class="printed">PRINTED IN INDIA</span>
        </div>
    </body>
</html>
```
```
style.css
body
{
    background-image: url(2.png);
}
.items
{
         
        
    
    width: 90%;
    background-color: silver;
    border-left: solid 6px black;
    padding: 25px;
    margin: 60px auto;
    position:relative;
    left:-49;
            
        
}
.author
{
    image-rendering: url(1.jpg);
    width: 90%;
    background-color: snow;
    border-left: solid 6px black;
    padding: 25px;
    margin: 60px auto;
    position:relative;
    left:-49
    
}
.profile-img
 {
    width: 85px;
    height: 85px;
    object-fit: cover;
    border-radius: 5px;
    margin-right: 15px;
 }
.footer
{
     width: 90%;
    background-color: yellow;
    border-left: solid 6px black;
    padding: 25px;
    margin: 60px auto;
    position:relative;
    left: -30px;
    bottom:0%;
}
```

## OUTPUT:
![alt text](<Screenshot 2025-12-11 205638.png>)

## RESULT:
The program for designing book back cover page using HTML and CSS is completed successfully.
