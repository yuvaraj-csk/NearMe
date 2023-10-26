# Ex04 Places Around Me
## Date:30/09/2023
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
<html>
<head>
<title> Image Map </title>
</head>
<body>
<h1 align="center">
<font color="red"><b>kanchipuram</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Places Around Me</b></font>
</h3>
<center>
<img src="mapplace.png" usemap="#MyCity" height="782" width="1897">
<map name="MyCity">
<area shape="rectangle" coords="905,567,1011,614" href="silk.html" title="PS silk sarees">
<area shape="circle" coords="619,619,40" href="ground.html" title="collector ground">
<area shape="circle" coords="641,147,32" href="theatre.html" title="babu theatre">
<area shape="rectangle" coords="1003,131,1037,166" href="temple.html" title="vazhakaratheeswarar temple">
<area shape="rectangle" coords="258,511,288,538" href="school.html" title="bharathi school">
</map>
</center>
</body>
</html>


```

## OUTPUT
![Alt text](<sree/mapapp/static/image map output.png>)
![Alt text](<sree/mapapp/static/babu cinema output.png>)
![Alt text](<sree/mapapp/static/bharathi output.png>)
![Alt text](<sree/mapapp/static/collector output.png>)
![Alt text](<sree/mapapp/static/silk sarees.png>)
![Alt text](<sree/mapapp/static/temple output.png>)


## RESULT
The program for implementing image maps using HTML is executed successfully.
