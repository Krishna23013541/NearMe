# Ex04 Places Around Me
## Date: 27.03.2024

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
            Chennai Central
        </title>
    </head>
    <body>
        <h1 align="center">
            <font color="red"><b>Chennai Central</b></font>
        </h1>
        <h3 align="center">
            <font color="black"><b>KRISHNA KUMAR R (212223230107)</b></font>
        </h3>
        <center>
            <img src="map.png" usemap="#MyCity" height="610" width="1450">
            <map name="MyCity">
                <area shape="rect" coords="805,162,1226,539" href="home.html" title="My Home Town">
                <area shape="circle" coords="564,8,238" href="stadium.html" title="Jawaharlal Nehru Stadium">
                <area shape="circle" coords="684,446,103" href="park.html" title="Chennai Park">
                <area shape="circle" coords="1317,133,142" href="temple.html" title="Kandhakottam Temple">
                <area shape="circle" coords="216,462,128" href="hotel.html" title="Hotel Joyce">
                <area shape="circle" coords="1337,467,273" href="hostel.html" title="Madras Medical College Hostel">

            </map>
        </center>
    </body>
</html>

stadium.html

<html>
    <head>
        <title>Jawaharlal Nehru Stadium</title>
    </head>
    <body bgcolor="brown">
    <h1 align="center">
        <font color="pink"><b>Nehru Stadium</b></font>
    </h1>
    <h3 align="center">
        <font color="orange">Stadium<b></b></font>
    </h3>
    <hr size="3" color="yellow">
    <p align="justified">
        <font face="Georgia" size="5">
            History. The Jawaharlal Nehru Stadium was constructed by the Government of India to host the 1982 Asian Games.
            A total of 3,411 athletes from 33 National Olympic Committees (NOCs) participated in these games, competing in 196 events in 21 sports and 23 disciplines.
            So one could choose either a center seat on the ground floor or consider the first two rows of the balcony.
            The balcony view provides a better viewing experience as one is looking"down" at the stage.
            
        </font>
    </p>

    </body>
</html>

park.html

<html>
    <head>
        <title>Chennai Park</title>
    </head>
    <body bgcolor="yellow">
    <h1 align="center">
        <font color="red"><b>Chennai</b></font>
    </h1>
    <h3 align="center">
        <font color="blue"><b>Park</b></font>
    </h3>
    <hr size="3" color="oraange">
    <p align="justified">
        <font face="Georgia" size="5">
            Ancient temples, vibrant arts, natural wonders and a bustling culinary scene make Chennai, the capital of Tamil Nadu, one of the most popular tourist destinations in the southern fringes of the country.
            Located on the Coromandel Coast, this busy metropolis was formerly called Madras.
            Tidal Park is one of the first and largest IT parks in Chennai and is fortunately quite close to Hablis Hotel. 
            The distance between the corporate park and the business hotel is 6.6 km and takes 12 minutes to travel.

        </font>
    </p>

    </body>
</html>

temple.html

<html>
    <head>
        <title>Kandakottam Temple</title>
    </head>
    <body bgcolor="grey">
    <h1 align="center">
        <font color="white"><b>Temple</b></font>
    </h1>
    <h3 align="center">
        <font color="white"><b>Kandakottam</b></font>
    </h3>
    <hr size="3" color="yellow">
    <p align="justified">
        <font face="Georgia" size="5">
            The temple is dedicated to lord murugan worshipped as kandasamy and is a live in devine .
            The vigraham is said to be brought from thiruporur a village near chennai on the way to mamallapuram .
            The temple have a big tank known as saravana poigai.
            The Kandha kottam temple is associated with the life of the saint Ramalinga Swamigal (also known as Vallalar), who composed 'Deiva mani malai' here.
            Saint Ramalingam (1823 to 1874) was a small child when he relocated with his mother to Chennai in 1826;  after the death of his father in 1824
        </font>
    </p>

    </body>
</html>

hotel.html

<html>
    <head>
        <title>Hotel Joyce</title>
    </head>
    <body bgcolor="pink">
    <h1 align="center">
        <font color="red"><b>Joyce</b></font>
    </h1>
    <h3 align="center">
        <font color="purple"><b>Famous Hotel</b></font>
    </h3>
    <hr size="3" color="white">
    <p align="justified">
        <font face="Georgia" size="5">
            From all the Budget hotels in Chennai, Hotel Joyce is very much popular among the tourists. 
            A smooth check-in/check-out process, flexible policies and friendly management garner great customer satisfaction for this property. 
            The Hotel has standard Check-In time as 02:00 PM and Check-Out time as 12:00 PM.
        </font>
    </p>

    </body>
</html>

hostel.html

<html>
    <head>
        <title>Madras Medical College Hostel</title>
    </head>
    <body bgcolor="green">
    <h1 align="center">
        <font color="purple"><b>College & Hostel</b></font>
    </h1>
    <h3 align="center">
        <font color="orange"><b>Nursing Student Medical College Hostel</b></font>
    </h3>
    <hr size="3" color="orange">
    <p align="justified">
        <font face="Georgia" size="5">
            Madras Medical College is the second the oldest medical college in India, established in 1835, just after Calcutta Medical College.
            It was originally founded in 1664 to treat soldiers of the British East India Company, but it has since become a prestigious and prosperous institution of medical education and service.
            Madras Medical College & Government General Hospital
            The no. 1 medical college in Chennai is Madras Medical College & Government General Hospital. The annual tuition fee of the college is INR 68,000 and the average placement package offered by the college is INR 7.2 LPA. The overall Shiksha rating of the college 4.6 out of 5.
        </font>
    </p>

    </body>
</html>

```

## OUTPUT

![alt text](1.png)

![alt text](2.png)

![alt text](3.png)

![alt text](4.png)

![alt text](5.png)

![alt text](6.png)

![alt text](7.png)

## RESULT
The program for implementing image maps using HTML is executed successfully.
