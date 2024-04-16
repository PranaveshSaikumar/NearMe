# Ex04 Places Around Me
## Date: 
14/04/2024
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
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=+, initial-scale=1.0">
    <title>Document</title>
</head>
<style>
    * { margin: 0;}
    </style>
    <script>
        function coordinate(event){
            let x = event.clientX;
            let y = event.clientY;
            document.getElementById("text1").value = x;
            document.getElementById("text2").value = y;
        }
    </script>
<body>
    <img src="C:\Users\admin\Pictures\Screenshots\googleimg.png" width="1550" height="600"
    usemap="#MapNew" onmousemove="coordinate(event)">
    <MAP name="MapNew">
        <AREA shape="RECT" coords="860,260,1050,305"
    href="https://saveetha.ac.in/" title="Saveetha Engineering College">
        <AREA shape="RECT" coords="1050,260,1160,315"
    href="https://dmice.ac.in/" title="DMI College of Engineering">
        <AREA shape="RECT" coords="1230,285,1360,340"
    href="https://www.lit.edu.in/" title="Loyola Institute of Technology">
    </MAP>
    <br>
    X-coordinate
    <input type="text" id="text1">
    <br>
    <br>
    Y-coordinate
    <input type="text" id="text2">
</body>
</html>
   ``` 

## OUTPUT

![Ex 4 OUTPUT](https://github.com/PranaveshSaikumar/NearMe/assets/151001393/fd21e183-10fb-4a94-8c25-7d2698d2b3b8)

![Ex4 output](https://github.com/PranaveshSaikumar/NearMe/assets/151001393/f9ba1c7e-52e8-471d-b123-9b83394ce130)

![image](https://github.com/PranaveshSaikumar/NearMe/assets/151001393/66a281e3-3c12-4af7-86cb-eeb59995bbe8)


## RESULT
The program for implementing image maps using HTML is executed successfully.
