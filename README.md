# Ex04 Places Around Me
## Date: 09.11.2025

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
    <title>My City</title>
</head>
<body>
    <h1 align="center">
        <font color="red"><b>NELLORE</b></font>
    </h1>
    <h3 align="center">
        <font color="blue"><b> pothu summanth (212224240115)</b></font>
    </h3>
    <center>
        <img src="map.png" usemap="#MyCity" height="610" width="1450">
        <map name="MyCity">

            <!-- 1. Jonnawad -->
            <area shape="circle" coords="300,120,30" href="jonnawada.html" title="jonnawada">

            <!-- 2. Nellore -->
            <area shape="circle" coords="590,200,30" href="nellore.html" title="Nellore">

            <!-- 3 .Mypadu Beach -->
            <area shape="circle" coords="1230,20,35" href="mypadu.html" title="Mypadu Beach">

            <!-- 4. Kovur -->
            <area shape="circle" coords="640,20,25" href="kovur.html" title="Kovur">

            <!-- 5. Narasimhakonda -->
            <area shape="circle" coords="250,160,30" href="Narasimhakonda.html" title="Narasimhakonda">

        </map>
    </center>
</body>
</html>

nellore.html

<html>
<head>
    <title>My Home Town</title>
</head>
<body bgcolor="lightyellow">
    <h1 align="center">
        <font color="red" size="6">Nellore</font>
    </h1>
    <h2 align="center">
        <font color="blue">Sri Nellore city – prominent city</font>
    </h2>
    <hr size="2" color="red">
    <font face="calibri" size="5">
        Nellore is a prominent city in Andhra Pradesh, well known for its rich history, culture, and temples. One of the famous devotional centers is the Sri Ranganathaswamy Temple, which attracts thousands of devotees each year. The temple is renowned for its beautiful architecture, peaceful ambiance, and importance in spiritual practices.
    </font>
</body>
</html>

mypadu.html

<html>
<head>
    <title>mypadu beach</title>
</head>
<body bgcolor="skyblue">
    <h1 align="center">
        <font color="red" size="6">Mypadu</font>
    </h1>
    <h2 align="center">
        <font color="blue">Mypadu Beach – Tourist Attraction</font>
    </h2>
    <hr size="2" color="red">
    <font face="calibri" size="5">
        Mypadu is a beautiful coastal village located in Andhra Pradesh, best known for its serene beach and scenic surroundings. Mypadu Beach is a popular destination for tourists, offering stunning views, clean sands, and peaceful waves. The area provides ample opportunities for relaxation, family outings, and photography, making it one of the notable attractions near Nellore.
    </font>
</body>
</html>

jonnawada.html

<html>
<head>
    <title>Jonnawada</title>
</head>
<body bgcolor="lavender">
    <h1 align="center">
        <font color="red" size="6">Jonnawada</font>
    </h1>
    <h2 align="center">
        <font color="blue">Sri Kamakshi Ammavari Temple – Devotional Centre</font>
    </h2>
    <hr size="2" color="red">
    <font face="calibri" size="5">
        Jonnawada is a renowned devotional center near Nellore, Andhra Pradesh, celebrated for the ancient Sri Kamakshi Ammavari Temple. The temple's tranquil and scenic surroundings encourage spirituality and devotion. With its rich cultural heritage and beautiful temple architecture, Jonnawada attracts devotees throughout the year seeking blessings and peace.
    </font>
</body>
</html>

narasimhakonda.html

<html>
<head>
    <title>My Home Town</title>
</head>
<body bgcolor="peachpuff">
    <h1 align="center">
        <font color="red" size="6">Narasimha Konda</font>
    </h1>
    <h2 align="center">
        <font color="blue">Narasimha Swamy Temple – Devotional Centre</font>
    </h2>
    <hr size="2" color="red">
    <font face="calibri" size="5">
        Narasimha Konda is a famous hill near Jonnawada and Nellore in Andhra Pradesh, widely known for its ancient Narasimha Swamy Temple. The temple is dedicated to Lord Narasimha, an incarnation of Lord Vishnu, and attracts a large number of devotees seeking blessings and tranquility. The scenic location, spiritual ambiance, and historical importance make Narasimha Konda a prominent devotional center and a peaceful spot for worship and meditation.
    </font>
</body>
</html>

kovur.html

<html>
<head>
    <title>kovur</title>
</head>
<body bgcolor="lightgreen">
    <h1 align="center">
        <font color="red" size="6">Kovur</font>
    </h1>
    <h2 align="center">
        <font color="blue">Sri Subrahmanyeswara Swamy Temple – Devotional Centre</font>
    </h2>
    <hr size="2" color="red">
    <font face="calibri" size="5">
        Kovur is a notable town near Nellore, Andhra Pradesh, known for its ancient temples and cultural heritage. The famous Sri Subrahmanyeswara Swamy Temple is a key devotional center in Kovur, attracting pilgrims for its spiritual ambiance and beautiful architecture. The temple surroundings provide a peaceful atmosphere for worship and community gatherings.
    </font>
</body>
</html>


```

## OUTPUT
![WhatsApp Image 2025-11-10 at 11 42 11_d2a6cad0](https://github.com/user-attachments/assets/2dc8d696-0487-4475-ad13-6ed329d2cbe9)



## RESULT
The program for implementing image maps using HTML is executed successfully.
