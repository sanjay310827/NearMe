# Ex04 Places Around Me
## Date: 30.09.2025

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
    <img src="map.png" usemap="#image-map" >

        

<map name="image-map">
    <area target="" alt="sadras dutch fort" title="sadras dutch fort" href="fort.html" coords="1398,231,1666,366" shape="rect">
    <area target="" alt="tasmac shop" title="tasmac shop" href="shop.html" coords="1061,551,1129,476,1243,471,1305,546,1254,605,1129,610" shape="poly">
    <area target="" alt="kalpakkam beach" title="kalpakkam beach" href="beach.html" coords="1447,631,69" shape="circle">
    <area target="" alt="retreat resort" title="retreat resort" href="resort.html" coords="733,19,1006,136" shape="rect">
    <area target="" alt="cs wellspring" title="cs wellspring" href="spring.html" coords="296,739,132" shape="circle">
</map>
            
    
</body>
</html>


fort.html
<html>
    <head>

    </head>
    <body bgcolor="yellow">
        <h2 align="center">kalpakkam</h2>
        <br><br>
        <h3 align ="center">sadras dutch fort</h3>
        <hr>
        <br><br>
        <h4>The Sadras Dutch Fort is a partially ruined, ASI-protected monument in Tamil Nadu, India, originally built by the Dutch for commerce and defense, featuring a large granary and stables now mostly gone. The surviving structures, including strong laterite walls and bastions, alongside a well-maintained Dutch cemetery with 17th and 18th-century graves, offer insight into the fort's commercial and military history before its capture by the British in 1818. </h4>
        

    </body>
</html>

spring.html
<html>
    <head>

    </head>
    <body bgcolor="gray">
        <h2 align="center">kalpakkam</h2>
        <br><br>
        <h3 align ="center">cs wellspring</h3>
        <hr>
        <br><br>
        <h4>CS Wellspring is a luxury wellness resort and investment opportunity by Sigaram Holdings Pvt. Ltd., located near Mahabalipuram, offering a combination of vacation amenities and holistic wellness services like naturopathy, yoga, and meditation, set in an eco-friendly environment with villas and beautiful landscapes, aiming to provide a rejuvenating retreat for guests and a lucrative opportunity for investors.  </h4>

    </body>
</html>

resort.html
<html>
    <head>

    </head>
    <body bgcolor="azure">
        <h2 align="center">kalpakkam</h2>
        <br><br>
        <h3 align ="center">retreat resort</h3>
        <hr>
        <br><br>
        <h4>A "retreat resort" is a hospitality establishment offering a peaceful, comfortable setting for relaxation, healing, or personal growth, often with minimalist and tranquil environments, though some may incorporate luxury and comfort like traditional resorts. These destinations provide services such as elegant accommodations, dining, swimming pools, lush gardens, and other amenities like hot tubs or fitness facilities, serving as a convenient base for exploring local attractions while ensuring a relaxing experience. </h4>

    </body>
</html>

beach.html
<html>
    <head>

    </head>
    <body bgcolor="blue">
        <h2 align="center">kalpakkam</h2>
        <br><br>
        <h3 align ="center">kalpakkam beach</h3>
        <hr>
        <br><br>
        <h4>Kalpakkam beach offers a quiet, family-friendly atmosphere with a blend of natural scenery and modern amenities, including calm waters and rocky patches suitable for relaxed strolls and observing marine life. The beach's environment is influenced by local efforts to manage weed growth and a tsunami wall for protection, along with the surrounding clean, green environment of the township itself. It's a place where visitors can enjoy a laid-back escape while being close to other points of interest, like the Sadras Dutch Fort and the Mahabalipuram UNESCO World Heritage Site. </h4>

    </body>
</html>

shop.html
<html>
    <head>

    </head>
    <body bgcolor="cyan">
        <h2 align="center">kalpakkam</h2>
        <br><br>
        <h3 align ="center">tasmac shop</h3>
        <hr>
        <br><br>
        <h4>The retail outlets do not have individual names. Instead they are named as "TASMAC Shop XXX", where XXX stands for the outlet number. They are popularly referred to as "wine shops", though they sell other kinds of liquor as well. About half the outlets have bars attached to them.</h4>

    </body>
</html>
```

## OUTPUT

![alt text](<Screenshot 2025-09-30 091522-1.png>)

![alt text](<Screenshot 2025-09-30 091549.png>)

![alt text](<Screenshot 2025-09-30 091627.png>)

![alt text](<Screenshot 2025-09-30 091655.png>)

![alt text](<Screenshot 2025-09-30 091712.png>)

![alt text](<Screenshot 2025-09-30 091747.png>)






## RESULT
The program for implementing image maps using HTML is executed successfully.
