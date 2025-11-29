# Ex03 Places Around Me
## Date: 29/11/2025

## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google as an image.

### STEP 3
Insert the image using ```<img>``` tag and link it to the map.

### STEP 4
Using ```<map>``` tag name the map.

### STEP 5
Create clickable regions in the image using ```<area>``` tag.

### STEP 6
Write HTML programs for all the regions identified.

### STEP 7
Execute the programs and publish them.

## CODE
```
mapapp.html
<html>
    <head>
        <title>my city</title>
    </head>
    <body>
        <h1 align="center">TIRUPATTUR</h1>
        <h3 align="center">SOWBARNIKA M P (25015490)</h3>


        <img src="map.png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="sacred heart college" title="sacred heart college" href="college.html" coords="670,236,867,329" shape="rect">
    <area target="" alt="Hotel hills tirupattur" title="Hotel hills tirupattur" href="hotel.html" coords="615,478,722,645,754,455,672,427" shape="poly">
    <area target="" alt="Uma selvi hospital" title="Uma selvi hospital" href="hospital.html" coords="302,546,79" shape="circle">
    <area target="" alt="AVR swarna mahal" title="AVR swarna mahal" href="jewellery.html" coords="877,345,1251,389,877,417" shape="poly">
    <area target="" alt="Sri rajakaali amman siddar  peedam" title="Sri rajakaali amman siddar  peedam" href="temple.html" coords="1467,574,1662,663" shape="rect">
</map>
college.html
<html>
    <head>
        <title>Sacred heart college</title>
    </head>
    <body bgcolor="pink">
        <h1>Sacred heart college</h1>
        <p>Sacred Heart College (SHC), Tirupattur, is an autonomous, minority institution affiliated with Thiruvalluvar University in Tamil Nadu, founded in 1951 by Fr. Joseph Carreno SDB. Administered by the Salesians of Don Bosco, the college focuses on providing higher education with an emphasis on integral human development for poor and rural youth, while also being open to students of all backgrounds.</p>
    </body>
    
</html>
hotel.html
<html>
    <head>
        <title>Hotel hills tirupattur</title>
    </head>
    <body bgcolor="yellow">
        <h1>Hotel hills tirupattur</h1>
        <p>Hotel Hills in Tirupattur is a 3- to 3.5-star hotel located on Krishnagiri Road, near the Tirupattur Bus Stand. It offers a range of rooms, dining options, and amenities like free Wi-Fi, air conditioning, and an in-house restaurant that serves both vegetarian and non-vegetarian food. The hotel is also equipped with a laundry service, parking, and a fitness center.</p>
    </body>
</html>
hospital.html
<html>
    <head>
        <title>Uma selvi hospital</title>
    </head>
    <body bgcolor="green">
        <h1>Uma selvi hospital</h1>
        <p>Uma Selvi Hospital in Tirupattur is a private hospital that operates 24/7. It is located on the Barugur - Thirupattur Rd.</p>
    </body>
</html>
temple.html
<html>
    <head>
        <title>Sri rajakali amman siddar peedam</title>
    </head>
    <body bgcolor="red">
        <h1>Sri rajakali amman siddar peedam</h1>
        <p>The Sri Rajakaliamman Siddhar Peetam is located in Agram village, Tirupattur taluk, near Tirupattur, Tamil Nadu. This ancient temple, dedicated to Goddess Rajakaliamman, is estimated to be around 500 years old. Its full address is Agram Village, Tirupattur Taluk, Tirupattur, Vellore District, Tamil Nadu, 635601.</p>
    </body>
</html>
jewellery.html
<html>
    <head>
        <title>AVR swarna mahal tirupattur</title>
    </head>
    <body bgcolor="blue">
        <h1>AVR swarna mahal tirupattur</h1>
        <p>No.123/B, Near Bus Stop, Palanisamy Road, Krishnagiri Road, Tirupattur-635601, Tamil Nadu</p>
    </body>
</html>

```

## OUTPUT

![alt text](<web map.png>)

![alt text](<Screenshot 2025-11-29 105547.png>)

![alt text](<Screenshot 2025-11-29 105605.png>)

![alt text](<Screenshot 2025-11-29 105651.png>)

![alt text](<Screenshot 2025-11-29 105718.png>)

![alt text](<Screenshot 2025-11-29 105741.png>)


## RESULT
The program for implementing image maps using HTML is executed successfully.
