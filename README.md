# Ex03 Places Around Me
## Date: 

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
~~~
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Ramanathapuram Map</title>
    </head>

    <body>

<img src="ramanathapuram_map.png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="beach" title="beach" href="beach.html" coords="1325,683,1479,794" shape="rect">
    <area target="" alt="temple" title="temple" href="temple.html" coords="587,482,63" shape="circle">
    <area target="" alt="bridge" title="bridge" href="bridge.html" coords="1060,633,1131,624,1125,560,1054,550" shape="poly">
    <area target="" alt="island" title="island" href="island.html" coords="1117,649,17" shape="circle">
</map>

    </body>
</html>
~~~
~~~
<html>
<head>
<title>Pamban Bridge</title>
</head>

<body>

<h1 align="center">
Pamban Bridge
</h1>

<img src="c:\Users\acer\Documents\web app\pambanimg02.png" width="500">

<p>
Pamban Bridge connects mainland India with Rameswaram.
It is India's first sea bridge and offers amazing ocean views.
</p>

</body>
</html>
~~~
~~~
<html>
<head>
<title>Dhanushkodi Beach</title>
</head>

<body>

<h1 align="center">
Dhanushkodi Beach
</h1>

<img src="beach.jpg" width="500">

<p>
Dhanushkodi is a beautiful beach town located at the
tip of Rameswaram island. It is famous for sea views,
sunrise and historical ruins.
</p>

</body>
</html>
~~~
~~~
<html>
<head>
<title>Kurusadai Island</title>
</head>

<body>

<h1 align="center">
Kurusadai Island
</h1>

<img src="island.jpg" width="500">

<p>
Kurusadai Island is known for marine biodiversity,
coral reefs and rare aquatic species near the Gulf of Mannar.
</p>

</body>
</html>
~~~
~~~
<html>
<head>
<title>Rameswaram Temple</title>
</head>

<body>

<h1 align="center">
Ramanathaswamy Temple
</h1>

<img src="temple.jpg" width="500">

<p>
Ramanathaswamy Temple in Rameswaram is one of the
famous Hindu pilgrimage sites dedicated to Lord Shiva.
It is known for its long corridors and beautiful pillars.
</p>

</body>
</html>
~~~


## OUTPUT


<img width="1693" height="893" alt="Screenshot 2026-05-22 182306" src="https://github.com/user-attachments/assets/726c804c-9b7b-463d-b551-f4c2a35ff7d2" />

<img width="1825" height="712" alt="Screenshot 2026-05-22 182314" src="https://github.com/user-attachments/assets/c6678aa0-f200-47a3-96e0-fd43c0d5c58a" />

<img width="1284" height="684" alt="Screenshot 2026-05-22 182323" src="https://github.com/user-attachments/assets/1f2778d8-17dd-4b90-ad2a-7d6f4712c597" />

<img width="1355" height="783" alt="Screenshot 2026-05-22 182333" src="https://github.com/user-attachments/assets/8503fc9b-7512-47d3-b40c-f8ec26af4ed7" />

<img width="1139" height="880" alt="Screenshot 2026-05-22 182403" src="https://github.com/user-attachments/assets/d3eb32d8-d724-403f-a55c-91106ea7bc55" />



## RESULT
The program for implementing image maps using HTML is executed successfully.
