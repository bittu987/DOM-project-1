Created DOM Project 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DOM_Project</title>
</head>
<body>
    <div id="Box">
        <p id="para"></p>
    </div>
<script>
        
 let box = document.getElementById("Box");

 box.style.height = "200px";
 box.style.width =  "300px";
 box.style.backgroundColor = "yellow ";
 box.style.color = "blue";
 box.style.margin = "18px";
 box.style.padding = "1px";
 box.style.fontSize = "19px";
 box.style.fontWeight = "bold";

  document.getElementById("para").innerHTML = "Hello, I'm a div!"

</script>
</body>
</html>
