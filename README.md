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
```
<head>
    <title>INDIA</title>
    <style>
        .bookpage{

            width: 400px;
            height: 600px;
            color:white;
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: 'Roquen';
            background-image: url("han.webp");
            background-size: cover;
        }
            
        
        .insight{
            color:rgb(8, 14, 14);
        
        }
        
        
        .hrstyle{
            width:100px;
        }
        .author{
        
            display: inline;
            position: relative;
            color:black;
            top:190px;
            
            font-family:Georgia;
            font-size: medium;
        }
        .booktitle{
            color:rgb(8, 8, 12);
            font-family: 'sans-serif';
            font-size: larger;
            text-align: center;
            position: relative;
            top: 30px;
        
        }
        .id {
            width:400px;
            position: relative;
            top:180px;
            
        }
        .pub{
            color:rgb(17, 3, 3);
            font-size: medium;
            position: relative;
            top:155px;
            left:330px;
        }
        .ed{
            color:rgb(182, 21, 21);
            font-size: medium;
            font-family: Verdana;
            position:relative;
            top:90px;
        
        }
        .subtitle{
            color:rgb(59, 113, 133);
            font-family:unicorn;
            font-size: large;
            position: relative;
            top:60px;
        }
        .mypic{
            position: relative;
            top: 125px;
            left: 260px;
            width: 90px;
            height: 100px;
            background-size:contain;
        }
        </style>
        <title>Book Cover Page</title>
        </head>
        <body>
        <div class="bookpage">
            <div class="insight">
                SEC INSIGHT 
            </div>
            <div class="hrstyle">
                <hr style="color:rgb(27, 23, 16)">
            </div>
            <div class="booktitle">
                <h1>THE PERFECT </h1>
                
            </div>
           
            <div class="subtitle">
                <h1 align="center">Top seller of 2023</h1>
            </div>

            <div class="mypic" >
                <img src="HAN PHO.jpeg" width="120" height="140" style="border-radius: 50%;" >
            </div>
            <div class="id">
                <hr style="color:rgb(10, 12, 13)">
            </div>
            <div class="author">
               <p><b>HANSHIKA VARTHINI R</b></p>
            </div>
            <div class="pub">
                SEC
            </div>
            <div class="ed">
                <b>Extended EDITION</b>
            </div>
        </div>
        </body>
        

</html>
```

## OUTPUT:
![alt text](<WhatsApp Image 2024-05-09 at 22.22.29_a788f296.jpg>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
