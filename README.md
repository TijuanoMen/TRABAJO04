<html> 
 <head> 
 <meta name="viewport" content="width=device-width, initial-scale=1"> 
  <tittle><h1>CAMBIA-DE-COLOR-Y-DE-LETRA</h1></tittle> 
</head> 
 
<body> 
 
 <!--Default Color is Black--> 
 <input type="color" value="#00FF00" />
 <div id="t_div">"La parálisis del sueño es algo que me sucede desde los 14,por lo general solo era la sensación de no poderme mover y estar consciente al respecto.

Una de tantas veces pude escuchar como alguien entró a mi cuarto y comenzó a abrazarme hasta lastimarme la espalda. Me asusté mucho porque eso no era "normal" dentro de lo que ya me había pasado antes. Empecé a tratar de soltarme pero mientras lo intentaba sentía como, lo que sea que estaba ahí, se enojaba y me gruñía. Cuando al fin pude moverme, sentí un escalofrío en todo mi cuerpo y me dolía muchísimo la espalda. Aún tengo parálisis del sueño y no he tenido una experiencia igual a esa, sigo tratando de entender qué sucedió esa ocasión"</div> 
 
 <button type="button" onclick="set_color();">Change Color</button> 
 
 <script> 
  function set_color() 
  { 
   document.getElementById("t_div").style.color = "red"; 
  } 
 </script> 
 
</body> 
 
</html>
