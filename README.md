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
<!DOCTYPE html>
<html>

<head>
    <title>Music</title>
    <style>
        .bookpage{

            width: 400px;
            height: 600px;
            color:black;
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url('front coverrrr.png');
            background-size: cover;
        }
            
        
        .insight{
            color:azure;
        
        }
        
        
        .hrstyle{
            width:100px;
        }
        .author{
        
            display: inline;
            position: relative;
            color:rgb(25, 12, 46);
            top:270px;
            
            font-family:Georgia;
            font-size: medium;
        }
        .booktitle{
            color:rgb(0, 0, 0);
            font-family: 'Verdana', Courier, monospace;
            font-size: larger;
            text-align: center;
            position: relative;
            top: 30px;
        
        }
        .id {
            width:400px;
            position: relative;
            top:280px;
            
        }
        .pub{
            color:rgb(247, 243, 242);
            font-size: large;
            position: relative;
            top:235px;
            left:330px;
        }
        .ed{
            color:rgb(15, 184, 184);
            font-size: medium;
            font-family: Verdana;
            position:relative;
            top:190px;
        
        }
        .subtitle{
            color:rgb(0, 0, 0);
            font-family:Verdana;
            font-size: large;
            position: relative;
            top:40px;
        }
        .mypic{
            position: relative;
            top: 250px;
            left: 300px;
            width: 90px;
            height: 80px;
            background-size:contain;
        }
        </style>
        <title>Book Cover Page</title>
        </head>
        <body>
        <div class="bookpage">
            <div class="insight">
                MACHINE LEARNING
            </div>
            <div class="hrstyle">
                <hr style="color:blanchedalmond">
            </div>
            <div class="booktitle">
                <h1>INSIGHTS OF ML</h1></div>
            <div class="subtitle">
                 USING AI IN 
                 
            </div>
            <div class="subtitle">
                 MACHINE LEARNING
            </div>

            <div class="mypic">
                <img src="c:\Users\admin\Pictures\Documents\Loki profile pic.jpg" width="100" height="100" >
            </div>
            <div class="id">
                <hr style="color:blanchedalmond">
            </div>
            <div class="author">
               <p><b>VEMBARASAN P</b></p>
            </div>
            <div class="pub">
                SEC
            </div>
            <div class="ed">
                <b>SPECIAL EDITION</b>
            </div>
        </div>
        </body>
</html>


```

## OUTPUT:
![WhatsApp Image 2024-05-12 at 21 46 50_41beb270](https://github.com/vembuu07/cover/assets/150772461/90b23570-3dc0-4a7f-9fd6-4b406d025991)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
