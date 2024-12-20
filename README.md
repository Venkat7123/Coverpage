# Ex.06 Book Front Cover Page Design
## Date: 01/12/2024

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
    <title>Book Cover Page</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">

    <link
        href="https://fonts.googleapis.com/css2?family=Dancing+Script:wght@400..700&family=Lobster&family=Orbitron:wght@400..900&family=Permanent+Marker&family=Sour+Gummy:ital,wght@0,100..900;1,100..900&display=swap"
        rel="stylesheet">
    <link
        href="https://fonts.googleapis.com/css2?family=Caveat:wght@400..700&family=Dancing+Script:wght@400..700&family=Lobster&family=Orbitron:wght@400..900&family=Permanent+Marker&family=Sour+Gummy:ital,wght@0,100..900;1,100..900&display=swap"
        rel="stylesheet">
    <style>
        .image {
            margin-left: 30%;
            width: 480px;
            height: 640px;
            position: relative;
        }
        
        .content1 {
            margin-left: 31%;
            position: absolute;
            top: 3%;
            color: rgb(67, 43, 43);
            font-size: 20px;
            line-height: 1.5;
            font-family: "Orbitron", sans-serif;
            font-optical-sizing: auto;
            font-style: normal;
        }

        .id {
            margin-left: 33%;
            position: absolute;
            top: 13%;
            color: black;
            font-size: 18px;
            line-height: 1.5;
            font-family: "Dancing Script", cursive;
            font-optical-sizing: auto;
            font-style: normal;
            right: 36%;
        }
        .content2 {
            margin-left: 28%;
            position: absolute;
            top: 21%;
            left: 4%;
            font-style: italic;
            width: 30%;
            color: rgb(159, 218, 254);
            font-size: 20px;
            line-height: 1.8;
        }

        .photo {
            position: absolute;
            bottom: 33%;
            width: 220px;
            right: 32%;
        }

        .line {
            position: absolute;
            bottom: 33%;
            left: 30.4%;
            width: 37.3%;
            height: 2px;
            background-color: black;
        }

        .line2 {
            position: absolute;
            bottom: 18.5%;
            left: 30.4%;
            width: 37.3%;
            height: 2px;
            background-color: black;
        }

        .nam {
            margin-left: 30%;
            position: absolute;
            bottom: 25%;
            left: 4%;
            color: rgb(71, 71, 71);
            font-size: 22px;
        }

        .name {
            margin-left: 30%;
            position: absolute;
            bottom: 18%;
            left: 4%;
            color: rgb(158, 94, 21);
            font-size: 16px;
            font-family: "Caveat", cursive;
            font-optical-sizing: auto;;
            font-style: normal;
        }

        .q {
            bottom: 7%;
            margin-left: 33%;
            color: rgb(250, 163, 13);
            position: absolute;
            font-family: "Dancing Script", cursive;
            font-optical-sizing: auto;
            font-style: normal;
            font-size: 40px;
        }

        .au {
            bottom: 4%;
            right: 35%;
            position: absolute;
            font-family: "Dancing Script", cursive;
            font-optical-sizing: auto;
            font-style: normal;
            font-size: 20px;
            color: blanchedalmond;
        }
    </style>
</head>

<body>
    <div class="container">
        <div class="ima">
            <img src="bg.png" class="image" alt="">
        </div>
       
        <div class="content1">
            <h1 class="h">WORLD OF CODING</h1>
        </div>
        <div class="id">
            <h2>EDITION-1</h2>
        </div>
        
        <div class="content2">
            <h3>Code your dreams into reality! <br> Discover the magic of coding, <br> a skill that empowers you <br> to
                shape the
                digital world <br> and beyond.</h3>
        </div>
        <div>
            <div class="line"></div>
            <div class="contentn">
                <img src="code.png" class="photo" alt="">
            </div>
            <div>
                <h3 class="nam">Author</h3></div>
                <div class="name">
                <h1> S.VENKATACHALAM, B.Tech IT</h1>
                
            </div>
            <div>
                <h1 class="q">Creativity meets logic</h1>
                <h3 class="au"> ~ John Romero</h3>
            </div>
            <div class="line2"></div>

        </div>
    </div>

</body>

</html>
```
## OUTPUT:
![alt text](img.png)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
