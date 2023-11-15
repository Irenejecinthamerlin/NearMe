# Ex04 Places Around Me
## Date: 24/10/23

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
# CODE:
# mapapp.html
```
<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8"/>
        <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
        <title>MAP</title>
    </head>
    <body>
        <centre>
        <h1 align="center" style="font-size: 30px;">
            <u>IMAGE MAP</u> 
            <p>Ashmi.S 212221040021</p>
        </h1>
<img src="mapapp.png" usemap="#image-map">
<map name="image-map">
    <area target="" alt="Ponjesly hospital" title="Ponjesly hospital" href="ponjesly.html" coords="846,127,1039,195" shape="rect">
    <area target="" alt="St. Antony's Church Kanykulam" title="St. Antony's Church Kanykulam" href="church.html" coords="1556,226,1814,300" shape="rect">
    <area target="" alt="Krishna Kumar Orthopaedic hospital" title="Krishna Kumar Orthopaedic hospital" href="KrishnaK.html" coords="637,701,841,779" shape="rect">
    <area target="" alt="APN Furnitures" title="APN Furnitures" href="apn.html" coords="622,584,768,677" shape="rect">
    <area target="" alt="Village Panchayat office" title="Village Panchayat office" href="village.html" coords="1556,226,1814,300" shape="rect">
    <area target="" alt="Kanyakulam Panchayat Office" title="Kanyakulam Panchayat Office" href="kanyakulam.html" coords="1346,80,1529,160" shape="rect">
</map>
</centre>
    </body>
    </html>

```
# ponjesly.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PONJESLY SUPER SPECIALITY HOSPITAL</title>
    <style>
        h1{
            text-align: center;
            font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
            color:darkslategray;
        }
        p{
            text-align: justify;
            color:darkolivegreen;
            font-size: x-large;
            
        }
    </style>
</head>
<body>
    <h1>PONJESLY SUPER SPECIALITY HOSPITAL</h1>
    <br>
    <hr color="Brown">
<p>Ponjesly SUPER SPECIALITY HOSPITAL is a Technology based Multi-Super Speciality Hospital located in Nagercoil, Kanyakumari. Tamilnadu. Ponjesly Hospital is catering for head-to-toe health requirements of the human body & Mind. P.J.S.S.H Hospital is equipped with world standard equipments and imaging specialties to cover all speciality and super specialty facilities and services. Ponjesly Hospital believes in pin-point diagnosis and treatment, early recovery and less hospital stay.
    Health and education are integral for human development. Our Mission, is to provide true health education and advanced medical facilities to the needy patients of the society and support their
    physical, mental and social well being.</p>
</body>
</html>
```
# krishnaK.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>KRISHNA KUMAR ORTHOPAEDIC </title>
    <style>
        h1{
            text-align: center;
            font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
            color:darkslategray;
        }
        p{
            text-align: justify;
            color:darkolivegreen;
            font-size: x-large;
            
        }
    </style>
</head>
<body>
    <h1>KRISHNA KUMAR ORTHOPAEDIC</h1>
    <br>
    <hr color="Brown">
<p>
    Krishna Kumar Orthopaedic Hospital chooses innovation, quality, empathy, and precision in every aspect of its service. As Chennai's biggest Orthopaedic and Level 1 Trauma Centre, we are a fully accredited NABH Hospital with an expert team of hand-picked doctors and specialists. We have a legacy of more than 17 years in providing quality healthcare and successful services to more than 1.2 million trauma cases.
    
    Delivering better outcomes for every patient is at the heart of our service. To approach Trauma Care with extreme caution, we have a 24/7 availability of Trauma, Vascular, Neuro, Orthopaedic, Plastic, Oral & Maxillofacial and Gastroenterology specialists, who ensure critical care of the trauma patient needs during the golden hour.</p>
</body>
</html>
```
# apn.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>APN FURNITURE GALLERY</title>
    <style>
        h1{
            text-align: center;
            font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
            color:darkslategray;
        }
        p{
            text-align: justify;
            color:darkolivegreen;
            font-size: x-large;
            
        }
    </style>
</head>
<body>
    <h1>APN FURNITURE GALLERY</h1>
    <br>
    <hr color="Brown">
<p>APN Furniture is the leading Dealer in Nagercoil and Marthandam. We are here since 2003 in this industry. We always focus on our customer's satisfaction. Through our passion and experience in this industry, We are providing most innovative designs furniture and furnishing your home and that's make your home glorious.

    We are dedicated to the curation and creation of unique Teak wood furniture and interiors. Supported by the talented and innovative in-house designers,we offer furniture that are both traditional and contemporary in style.
    
    Last 18 years of experience,We are very thankful to our every customer for giving us the support.</p>
</body>
</html>
```
# kanyakulam.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>KANIYAKULAM PANCHAYAT </title>
    <style>
        h1{
            text-align: center;
            font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
            color:darkslategray;
        }
        p{
            text-align: justify;
            color:darkolivegreen;
            font-size: x-large;
            
        }
    </style>
</head>
<body>
    <h1>KANIYAKULAM PANCHAYAT</h1>
    <br>
    <hr color="Brown">
<p>
    Kaniyakulam is a Village in Rajakkamangalam Block in Kanniyakumari District of Tamil Nadu State, India. It is located 5 KM towards west from District head quarters Nagercoil. 6 KM from Rajakkamangalam. 730 KM from State capital Chennai
    
    Kaniyakulam Pin code is 629003 and postal head office is Vetturnimadam .
    
    Singarathoppu ( 1 KM ) , Christopher Nagar ( 1 KM ) , Rajalakshmi Nagar Extension ( 1 KM ) , Peruvilai ( 1 KM ) , Peruvilai ( 1 KM ) are the nearby Villages to Kaniyakulam. Kaniyakulam is surrounded by Rajakkamangalam Block towards South , Kurunthancode Block towards west , Thovala Block towards East , Thackalai Block towards west .
    
    Nagercoil , Padmanabhapuram , Karungal , Unnamalaikadai are the near by Cities to Kaniyakulam.</p>
</body>
</html>
```
# churuch.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>St. ANTONY'S CHURCH</title>
    <style>
        h1{
            text-align: center;
            font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
            color:darkslategray;
        }
        p{
            text-align: justify;
            color:darkolivegreen;
            font-size: x-large;
            
        }
    </style>
</head>
<body>
    <h1>St. ANTONY'S CHURCH </h1>
    <br>
    <hr color="Brown">
<p>St. Antony's Church is a Roman Catholic Church located at Chemmanvilai Village in Kanyakumari district of Tamil Nadu. The Church is located right in the middle of the Chemmanvilai village, is an important worship center that plays an important role in the lives of the local people. The church is under the control of the Roman Catholic Diocese of Kuzhithurai. On December 25, 1942, Rev Fr. Mathias of Madathattuvilai Parish helped to establish the small church and hold the first mass there.</p>
</body>
</html>
```

## OUTPUT
<img width="960" alt="12345" src="https://github.com/Irenejecinthamerlin/NearMe/assets/128350225/87735932-3a0c-4a46-ad36-1acbd473411b">

![image](https://github.com/Irenejecinthamerlin/NearMe/assets/128350225/5c32ad4d-0dc5-4ccc-9233-e1f4d3cbb750)


![image](https://github.com/Irenejecinthamerlin/NearMe/assets/128350225/135c7bc5-2dd1-41cc-83bf-ad3c46fce41a)


![image](https://github.com/Irenejecinthamerlin/NearMe/assets/128350225/2983db16-72d7-4409-b0e2-73514f2f4c57)


![image](https://github.com/Irenejecinthamerlin/NearMe/assets/128350225/d0450983-97a0-4749-a24e-6d8de3541e61)


![image](https://github.com/Irenejecinthamerlin/NearMe/assets/128350225/a3722f2f-d96b-4dff-b1f2-08197a79a84a)

## RESULT
The program for implementing image maps using HTML is executed successfully.
