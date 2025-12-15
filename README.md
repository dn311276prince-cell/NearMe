# Ex04 Places Around Me
## Date: 13/12/2025
dilipkumar R
25017135

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
'''
map.html

<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8" />
  <title>Anna Nagar Map</title>
</head>
<body>

<center>
    <h1><font color="blue"><b>Ashwin Ash</b></font></h1>
    <h2><font color="green"><b>Anna Nagar</b></font></h2>

    <!-- MAP IMAGE -->
    <img src="Screenshot 2025-12-11 200318.png" usemap="#annanagar" 
         height="610" width="1450" alt="Anna Nagar Map">

    <map name="annanagar">
        
        <!-- Example Coordinates -->
        <!-- 1. Anna Nagar Tower Park -->
        <area shape="circle" 
              coords="350,220,40" 
              href="tower_park.html" 
              title="Anna Nagar Tower Park">

        <!-- 2. VR Chennai Mall -->
        <area shape="rect" 
              coords="900,180,1050,310" 
              href="vr_mall.html" 
              title="VR Chennai Mall">

        <!-- 3. Thirumangalam Metro Station -->
        <area shape="circle" 
              coords="780,380,35" 
              href="metro.html" 
              title="Thirumangalam Metro">

        <!-- 4. Shanthi Colony  -->
        <area shape="poly" 
              coords="450,300,520,310,510,360,445,345" 
              href="shanthi_colony.html" 
              title="Shanthi Colony">

    </map>

</center>

</body>
</html>

metro.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <title>Thirumangalam Metro Station - Test</title>
</head>
<body bgcolor="purple">
  <center>
    <h1><font color="cyan"><b>Thirumangalam Metro Station</b></font></h1>
    <h3><font color="lime"><b>Ashwin Ash</b></font></h3>

    <hr>

    <font face="Georgia" size="4" color="white">
      <p align="justify">
        Thirumangalam Metro Station connects Anna Nagar to major parts of the city.
        The station improved daily commuting for many residents and reduced traffic
        congestion around the area. This is a test page to confirm the file opens.
      </p>
    </font>

  </center>
</body>
</html>

shanthi_colony.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <title>Shanthi Colony</title>
</head>
<body bgcolor="purple">
  <center>
    <h1><font color="cyan"><b>Shanthi Colony</b></font></h1>
    <h3><font color="lime"><b>Ashwin Ash</b></font></h3>
    <hr>
    <font face="Georgia" size="4" color="white">
      <p align="justify">
        Shanthi Colony is a popular residential and shopping street in Anna Nagar,
        known for its neat layout, shops, cafés and community-friendly atmosphere.
        It remains one of the pleasant neighbourhoods for families and visitors.
      </p>
    </font>
  </center>
</body>
</html>

tower_park.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <title>Anna Nagar Tower Park - Test</title>
</head>
<body bgcolor="purple">
  <center>
    <h1><font color="cyan"><b>Anna Nagar Tower Park</b></font></h1>
    <h3><font color="lime"><b>Ashwin Ash</b></font></h3>

    <hr>

    <font face="Georgia" size="4" color="white">
      <p align="justify">
        The Anna Nagar Tower Park is an iconic landmark featuring an observation tower and expansive
        green spaces. It is a favorite spot for families and morning walkers and provides a peaceful
        escape within the city. The park offers walking paths, play areas for children, and scenic
        views from the tower’s observation platform.
      </p>
    </font>

  </center>
</body>
</html>

vr_mall.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <title>VR Chennai Mall - Test</title>
</head>
<body bgcolor="purple">
  <center>
    <h1><font color="cyan"><b>VR Chennai Mall</b></font></h1>
    <h3><font color="lime"><b>Ashwin Ash</b></font></h3>

    <hr>

    <font face="Georgia" size="4" color="white">
      <p align="justify">
        VR Chennai, located near Anna Nagar, is one of the most modern shopping and entertainment
        destinations in the city. Opened in 2018, the mall represents a blend of art, luxury, and
        technology. It features a wide range of international and Indian brands, a multi-screen
        theater, restaurants, gaming zones, and cultural spaces.
      </p>
    </font>

  </center>
</body>
</html>


'''


## OUTPUT
<img width="1906" height="894" alt="Screenshot 2025-12-15 133709" src="https://github.com/user-attachments/assets/a17b607d-47db-4918-9ddb-095c6056fbe7" />
<img width="1917" height="904" alt="Screenshot 2025-12-15 140950" src="https://github.com/user-attachments/assets/b31967d4-62d8-46a3-a621-c2faf81bfb1e" />
<img width="1917" height="901" alt="Screenshot 2025-12-15 141045" src="https://github.com/user-attachments/assets/8d23b281-aa04-4d0c-a6dc-fefdb1682362" />
<img width="1919" height="902" alt="Screenshot 2025-12-15 141132" src="https://github.com/user-attachments/assets/d691c60f-8713-4e53-bd97-5b6b40855aac" />
<img width="1914" height="901" alt="Screenshot 2025-12-15 141237" src="https://github.com/user-attachments/assets/8c508e93-c80b-48dc-8a19-f8c0bcab1519" />







## RESULT
The program for implementing image maps using HTML is executed successfully.
