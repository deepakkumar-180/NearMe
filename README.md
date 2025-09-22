# Ex04 Places Around Me
## Date: 22.09.2025

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

<center><img src="Screenshot 2025-09-20 141915.png" usemap="#image-map"></center>

<map name="image-map" align="center">
    <area target="" alt="Meenakshi Amman Temple" title="Meenakshi Amman Temple" href="madurai1.html" coords="1120,55,82" shape="circle">
    <area target="" alt="maari Amman Temple" title="maari Amman Temple" href="madurai2.html" coords="884,617,653,553" shape="rect">
    <area target="" alt="Arulmigu Koodal Azhagar Temple" title="Arulmigu Koodal Azhagar Temple" href="madurai3.html" coords="692,408,754,378,818,385,827,417,820,483,681,506,587,451,603,389" shape="poly">
    <area target="" alt="Thirumalai Nayakkar Mahal" title="Thirumalai Nayakkar Mahal" href="madurai4.html" coords="1539,334,1276,442" shape="rect">
    <area target="" alt="sree sabarees" title="sree sabarees" href="madurai5.html" coords="589,102,671,104,639,239,729,170,513,287,539,76,511,95,438,168,461,184,513,219,548,241,541,79,523,67,568,134,539,76,550,271,529,106" shape="poly">
</map>

madurai1.html

<html>
    <head>
        <title> MEENKSHI AMMAN TEMPLE</title>
    </head>
    <body bgcolor="skyblue">
        <center>
        <h1>MEENAKSHI AMMAN TEMPLE</h1>
        <p>Madurai Meenakshi Sundareswarar temple was built by Pandyan Emperor Sadayavarman Kulasekaran I (r. 1190–1216). 
            He built the main portions of the three-storeyed Gopuram at the entrance of Sundareswarar Shrine and 
            the central portion of the Goddess Meenakshi Shrine, which are some of the earliest surviving parts of the temple. 
            The traditional texts call him a poet-saint king, additionally credit him with a poem called Ambikai Malai, 
            as well as shrines (koil) each for Natarajar and Surya near the main temple, Ayyanar in the east, Vinayagar in the south, 
            Kariamalperumal in the west and Kali in the north. He also built a Mahamandapam. Kulasekara Pandya was also a poet and 
            he composed a poem on Meenakshi named Ambikai Malai.[9] Maravarman Sundara Pandyan I built a gopuram in 1231, then called 
            Avanivendaraman, later rebuilt, expanded and named as Sundara Pandya Thirukkopuram.[9] Chitra gopuram (W), also known as
            Muttalakkum Vayil, was built by Maravarman Sundara Pandyan II (1238-1251). This gopuram is named after the frescoes
            and reliefs that depict secular and religious themes of Hindu culture. Maravarman Sundara Pandyan II also added a
            pillared corridor to the Sundareswara shrine and the Sundara Pandyan Mandapam.[9] It was rebuilt after the 14th-century
            damage, its granite structure was renovated by Kumara Krishnappar after 1595.[10]</p>
            </center>
    </body>
</html>

madurai2.html

<html>
    <head>
        <title>Marri Amman Temple</title>
    </head>
    <body bgcolor="blue">
        <center>
        <h1>marri amman temple</h1> 
        <p>A popular place to see in Madurai, Vandiyur Mariamman Teppakulam 
           is associated with the Vandiyur Mariamman Temple. A temple pond complex
           with a man-made island in the middle, it is primarily used for religious
           purposes. Located only 2 km from the famous Meenakshi Sundareswara Temple,
            it also attracts hordes of devotees. Considered as one of the largest
            temple tanks not only in Tamil Nadu but in South India, this temple
            tanks receives its water from the River Vaigai.</p>
        </center>

 
    </body>
</html>

madurai3.html

<html>
    <head>
        <title>Arulmigu Koodal Azhagar Temple</title>
    </head>
    <body bgcolor="purple">
        <center>
        <h1>Arulmigu Koodal Azhagar Temple</h1>
        <p>Dedicated to Lord Vishnu, Koodal Azhagar Temple/ Koodal Azhagar
             Koil is situated in the heart of Madurai city. In Tamil language, 
             Koodal stands for Madurai while Azhagar means ‘beautiful one’.
             This ancient temple of Madurai is located quite close to
            Meenakshi Amman Temple. A popular pilgrimage and an intricate
             part of Madurai tour, this temple is considered to be one of 
             the 108 Lord Vishnu’s holy abodes (divyadesams).</p>
        </center>
    </body>
</html>

madurai4.html

<html>
    <head>
        <title>Thirumalai Nayakkar Mahal</title>
    </head>
    <body bgcolor="pink">
        <center>
        <h1>Thirumalai Nayakkar Mahal</h1>
        <p>Tirumala Nayaka (reigned 1623–16 February 1659) was the ruler of Madurai 
            Nayak Dynasty in the 17th century. He ruled Madurai between 1623 and 
            1659. His contributions are found in the many splendid buildings and 
            temples of Madurai. He belongs to Balija caste.[3] His kingdom was 
            under constant threat from the armies of Bijapur Sultanate and the other 
            neighbouring Muslim kingdoms, which he managed to repulse successfully. His 
            territories comprised much of the old Pandya territories which included Coimbatore, 
            Tirunelveli, Madurai districts, Aragalur in southern Tamil Nadu and some territories 
            of the Travancore kingdom.</p>
        </center>
    </body>
</html>

madurai5.html

<html>
    <head>
        <title>sree sabarees</title>
    </head>
    <body bgcolor="orangr">
        <center>
        <h1>sree sabarees</h1>
        <p>Sree Sabarees is a hotel and vegetarian restaurant in Madurai, India, known for its authentic South Indian cuisine, particularly its dosas and idlis, and a casual, contemporary atmosphere suitable for families and college students. The hotel offers a buffet with free sweets, serves breakfast, lunch, and dinner, and has online booking services. It is centrally located near the Meenakshi Temple and the Madurai Railway Station.  
Background Details
Cuisine: Specializes in authentic South Indian vegetarian dishes, with particular praise for dosa, idli, podi, and chutneys. 
Atmosphere: Described as casual, contemporary, and trendy.
Guests: Accommodates families, college students, and groups.
Location: Centrally located in Madurai, close to the Meenakshi Temple and the Madurai Railway Station. 
Services: Offers online booking services and is known for its free sweets with breakfast. </p>
        </center>
    </body>
</html>



```

## OUTPUT
![alt text](<Screenshot 2025-09-22 131047.png>)
![alt text](<Screenshot 2025-09-22 131104.png>)
![alt text](<Screenshot 2025-09-22 131139.png>)
![alt text](<Screenshot 2025-09-22 131320.png>)
![alt text](<Screenshot 2025-09-22 131446.png>)
![alt text](<Screenshot 2025-09-22 131500.png>)

## RESULT
The program for implementing image maps using HTML is executed successfully.
