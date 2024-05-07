# Ex.06 Book Front Cover Page Design
## NAME: INDRAJA S
## REG NO: 212222043003
## Date: 7.5.24

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

HTML CODE

```
REG NO : 212222043003
DEVELOPED BY : INDRAJA S
<!DOCTYPE html>
<html>

<head>
    <title>FUNDAMENTALS OF WEB APP</title>
    <style>
        .bookpage{

            width: 400px;
            height: 700px;
            color:rgb(175, 50, 50);
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url("Background.jpg.jpeg");
            background-size: cover;
        }
        .insight{
            color:rgb(5, 16, 16);
            font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
            font-weight: 500;
        }
        
        
        .hrstyle{
            width:100px;
        }
        .author{
        
            display: inline;
            position: relative;
            color:rgb(255, 255, 255);
            top:200px;
            font-family:Georgia;
            font-size: medium;
        }
        .booktitle{
            color:rgb(14, 3, 9);
            font-family: 'copperplate gothic', Times, serif;
            font-size: larger;
            text-align: left;
            position: relative;
            top: 5px;
        
        }
        .id {
            width:400px;
            position: relative;
            top:180px;
            
        }
        .pub{
            
            font-size: medium;
            position: relative;
            top:70px;
            left:150px;
        }
        .ed{
            color:rgb(17, 0, 255);
            font-size: medium;
            font-family: Georgia, 'Times New Roman', Times, serif;
            position:relative;
            top:100px;
        
        }
        .subtitle{
            color:rgb(0, 0, 0);
            font-family: 'Times New Roman', Times, serif;
            font-size: large;
            position: relative;
            top:40px;
        }
        .mypic{
            position: relative;
            top: 135px;
            left: 260px;
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
               <strong>COMPUTER SCIENCE ENGINEERING</strong> 
            </div>
            <div class="hrstyle">
                <hr style="color:blanchedalmond">
            </div>
            <div class="booktitle">
                <h1>THEORY<br>COOKERY</h1></div>
            <div class="subtitle">
                 <strong>BASICS OF COOKING</strong> 
            </div>
            <div class="subtitle">
                 <strong>BEST SELLER</strong><br><br><br><br><br><br><br><br>
            </div>

            <div class="mypic">
                <img src="PASSPORT SIZE PIC.png" width="100" height="120" >
            </div>
            <div class="id">
                <hr style="color:blanchedalmond">
            </div>
            <div class="author">
                <style>
                
                    mark {
                        background-color: #000000; 
                        color: rgb(255, 255, 255);
                    }
                    </style>
               <p><b><strong><mark>INDRAJA S (212222043003)</mark></strong></b></p>
            </div>
            <div class="pub">
            
                 <style>
                
                    mark {
                        background-color: #fcfcfc; 
                        color: black;
                    }
                    </style>
                    <div class="pub">
                       
                    
                <strong><mark>SAVEETHA<br>PUBLICATIONS</mark></strong>
            
            </div>
           
        </div>
        </body>
        

</html>
```

CSS CODE
```
body
{
    margin: 0px;
    padding: 0px;

}
.background
{
    width: 100%;
    height: 100vh;
    background-image: url("C:\Users\Admin\Desktop\Background.jpg.jpeg");
    background-repeat: no-repeat;
    background-size: cover;
    background-position: center;
}


body {
    background-image: url("C:\Users\Admin\Desktop\Background.jpg.jpeg");
    background-repeat: no-repeat;
    background-size: cover;
}

.mypic {
    width: 35mm; 
    height: 45mm; 
}

```

## OUTPUT:

![EX 6 OUTPUT](https://github.com/indrajasukumar/cover/assets/145115195/3222cf59-90fe-4575-8c44-312a2f69f549)



## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
