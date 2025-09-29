# Ex04 Places Around Me
## Date: 28.09.2025

## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google.

### STEP 3
Using ```<map>``` tag name the map.

### STEP 4
Create clickable regions in the image using ```<area>``` tag.

### STEP 5
Write HTML programs for all the regions identified.

### STEP 6
Execute the programs and publish them.

## CODE
```
map.html
<html>
<head>
    <title>
        My City
        <link rel ="stylesheet" href="style.css">
    </title>
</head>
<body>
    <h1 align="center">kalpakkam</h1>
    <h3 align="center">sanjay (25016505)</h3>
    <img src="map.png" usemap="#MyCity" >

        

<map name="image-map">
    <area target="" alt="sadras dutch fort" title="sadras dutch fort" href="fort.html" coords="1398,231,1666,366" shape="rect">
    <area target="" alt="tasmac shop" title="tasmac shop" href="shop.html" coords="1061,551,1129,476,1243,471,1305,546,1254,605,1129,610" shape="poly">
    <area target="" alt="kalpakkam beach" title="kalpakkam beach" href="beach.html" coords="1447,631,69" shape="circle">
    <area target="" alt="retreat resort" title="retreat resort" href="resort.html" coords="733,19,1006,136" shape="rect">
    <area target="" alt="cs wellspring" title="cs wellspring" href="spring.html" coords="296,739,132" shape="circle">
</map>
            
    </center>
</body>
</html>


fort.html
<html>
    <head>

    </head>
    <body bgcolour="yellow">
        <h2 align="center">kalpakkam</h2>
        <br><br>
        <h3 align ="center">sadras dutch fort</h3>
        <hr>
        <br><br>


    </body>
</html>

spring.html
<html>
    <head>

    </head>
    <body bgcolour="gray">
        <h2 align="center">kalpakkam</h2>
        <br><br>
        <h3 align ="center">cs wellspring</h3>
        <hr>
        <br><br>


    </body>
</html>

resort.html
<html>
    <head>

    </head>
    <body bgcolour="azure">
        <h2 align="center">kalpakkam</h2>
        <br><br>
        <h3 align ="center">retreat resort</h3>
        <hr>
        <br><br>


    </body>
</html>

beach.html
<html>
    <head>

    </head>
    <body bgcolour="blue">
        <h2 align="center">kalpakkam</h2>
        <br><br>
        <h3 align ="center">kalpakkam beach</h3>
        <hr>
        <br><br>


    </body>
</html>

shop.html
<html>
    <head>

    </head>
    <body bgcolour="cyan">
        <h2 align="center">kalpakkam</h2>
        <br><br>
        <h3 align ="center">tasmac shop</h3>
        <hr>
        <br><br>


    </body>
</html>
```

## OUTPUT








## RESULT
The program for implementing image maps using HTML is executed successfully.
