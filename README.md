<html> 
 <head> 
 <meta name="viewport" content="width=device-width, initial-scale=1"> 
 <tittle>CAMBIA-DE-COLOR-Y-DE-LETRA</tittle> 
</head> 
 
<body> 
 
 <!--Default Color is Black--> 
 <input type="color" value="#00FF00" />
 <div id="t_div">Normal Text</div> 
 
 <button type="button" onclick="set_color();">Change Color</button> 
 
 <script> 
  function set_color() 
  { 
   document.getElementById("t_div").style.color = "red"; 
  } 
 </script> 
 
</body> 
 
</html>
