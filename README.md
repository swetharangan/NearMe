# Ex04 Places Around Me
## Date: 10.10.2024

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
<h1 align="center">
<font color="red"><b>MANGALORE</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Ragavi K (23012384)</b></font>
</h3>
<center>
<img src="map.png" usemap="#MyCity" height="610" width="1450">
<map name="MyCity">
<area shape="rect" coords="500,100,900,300" href="home.html" title="My Home Town">
<area shape="circle" coords="970,350,70" href="EB.html" title="mangalore EB office">
<area shape="circle" coords="150,100,70" href="temple.html" title="arunthavathai temple">
<area shape="circle" coords="1200,100,70" href="next place.html" title="kachimailur">
<area shape="circle" coords="480,550,70" href="shritemple.html" title="shri pachanamadam temple">
</map>
</center>
</body>
</html>

shritemple.html

<html>
<head>
<title>shri pachanamadam temple</title>
</head>
<body bgcolor="lightblue">
<h1 align="center">
<font color="red"><b>Mangalore</b></font>
</h1>
<h3 align="center">
<font color="red"><b>shri pachanamadam temple in my village</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
    Nestled within the serene embrace of a lush forest, the Shri Pachanamadam Temple stands as a sanctuary of tranquility and 
spiritual resonance. The temple, situated amidst the verdant expanse, exudes an aura of peace that is palpable from the moment one
enters its sacred grounds. The thick canopy of ancient trees forms a natural boundary, creating a hallowed space where the whispers
of leaves and the melodies of bird songs merge seamlessly with the rhythmic chants resonating from the temple walls.As one traverses the temple precincts,
 a sense of serenity envelops the soul, offering respite from the clamor of the outside world. The air is imbued with the fragrance of blooming flowers, 
 and the gentle rustle of leaves provides a soothing backdrop to the devotees' contemplative prayers. The temple's architecture, adorned with intricate 
carvings and vibrant hues, seamlessly integrates with the surrounding nature, creating a harmonious blend of divine worship and earthly beauty. In this
 sacred haven, visitors find solace, their spirits rejuvenated by the symbiotic relationship between the spiritual ambiance and the untamed wilderness
  that cradles the Shri Pachanamadam Temple in its embrace.
</p>
</body>
</html>

next place.html

<html>
<head>
<title>kachimailur</title>
</head>
<body bgcolor="lightblue">
<h1 align="center">
<font color="red"><b>Mangalore</b></font>
</h1>
<h3 align="center">
<font color="red"><b>Kachimailur-our neighbour village</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
    Kachimailur village, nestled beside our own, paints a picture of simplicity and warmth. The familiarity of neighboring fields and 
the shared horizon create a sense of community that transcends physical boundaries. In Kachimailur, life unfolds at a unhurried pace,
where the rhythm of daily routines is harmonized with the rustle of leaves and the distant hum of village life. It's a place where
the essence of rural living thrives, and neighbors are not just faces but extended family. The charm of Kachimailur lies in its 
uncomplicated beauty and the bonds woven through the ebb and flow of everyday existence.
</p>
</body>
</html>

temple.html

<html>
<head>
<title>arunthavathai temple</title>
</head>
<body bgcolor="lightblue">
<h1 align="center">
<font color="red"><b>Mangalore</b></font>
</h1>
<h3 align="center">
<font color="red"><b>Arunthavathai temple in my village</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
    Arunthavathai Temple, nestled in the heart of our village, is a place of spiritual solace and communal gathering. With its welcoming
entrance and vibrant hues, the temple stands as a symbol of devotion and unity. Surrounded by age-old trees and the gentle hum of 
village life, it creates a serene haven for those seeking moments of reflection. The temple bells resonate with the rhythm of prayers,
and the scent of incense wafts through the air, enveloping visitors in a sense of divine connection. Arunthavathai Temple, with its
simplicity and sacred atmosphere, plays a central role in our community, fostering a shared sense of faith and togetherness.   
</p>
</body>
</html>

EB.html

<html>
<head>
<title>mangalore EB office</title>
</head>
<body bgcolor="lightblue">
<h1 align="center">
<font color="red"><b>Mangalore</b></font>
</h1>
<h3 align="center">
<font color="red"><b>EB office in my village</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
    The EB (Electricity Board) office in our village stands as a hub of power management, ensuring that homes and businesses are lit up 
with the flick of a switch. Located conveniently within our community, the office is where locals go to address electrical concerns, 
set up new connections, or report outages. With its approachable staff and neat surroundings, the EB office is a place where the pulse
of our village's power supply is monitored and maintained. It serves as a crucial link between the residents and the seamless flow of 
electricity, ensuring that lights stay on and appliances hum with life in our quaint corner of the world.   
</p>
</body>
</html>

home.html

<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="lightblue">
<h1 align="center">
<font color="red"><b>Mangalore</b></font>
</h1>
<h3 align="center">
<font color="red"><b>My home town(Mangalore)</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
Mangalore, my village, is a coastal gem that unfolds the beauty of simple living. With its palm-fringed beaches, bustling markets, 
and the welcoming chatter of its people, Mangalore encapsulates a blend of tradition and modernity. The aroma of fresh seafood mingles 
with the fragrances of jasmine and incense as one navigates the vibrant streets. From the iconic temples to the rhythmic beats of 
traditional folk music, the essence of Mangalore lies in its cultural richness. Surrounded by lush greenery and bordered by the gentle 
waves of the Arabian Sea, the village offers a tranquil retreat for both residents and visitors alike. In Mangalore, every corner tells 
a story, and every sunrise brings a promise of another day steeped in the charm of coastal life.  
</p>
</body>
</html>
```

# OUTPUT

![1](https://github.com/Ragavikrishnan/NearMe/assets/144870428/633475b8-8d38-4d5a-8a21-c8cef921ad40)

![2 home town](https://github.com/Ragavikrishnan/NearMe/assets/144870428/295c2068-7569-4b59-82d9-4c0a1f600329)

![3 arunthavai](https://github.com/Ragavikrishnan/NearMe/assets/144870428/0f4def8a-7697-476c-acd7-64d888ed4f12)

![4 kachimailur](https://github.com/Ragavikrishnan/NearMe/assets/144870428/2be10568-29d9-467f-97fb-16147c4fe3b4)

![5 shri](https://github.com/Ragavikrishnan/NearMe/assets/144870428/fd40ae43-ba25-492c-8161-29ad549fc154)

![6 eb](https://github.com/Ragavikrishnan/NearMe/assets/144870428/0bc0444d-d61f-4e3f-aaec-2dda9c255f0f)




## RESULT
The program for implementing image maps using HTML is executed successfully.
