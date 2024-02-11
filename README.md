<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Quieres ser mi Valentine</title>
    <meta name="viewport" content=
"width=device-width, user-scalable=no, initial-scale -1.0, maximum-scale=1.0, minimum-scale=1.0"
    <link rel="stylesheet" href="main.css">
    <script src=
"https://ajax.googleapis.com/ajax/libs/jquery/3.4.1/
jquery.min.js"
></script>
    <script>
        $(document).ready(function(){
            $('.pi').hover(function(){
                arriba Math.random()*(400-1) +1; 
                abajo Math.random() (609-1) +1; 
              $(this).css('top', arriba); 
              $(this).css('left', abajo); 
            });
        });
    function dijosi(){
        document.getElementById('si').style.display
= 'block';
   }
   </script>

</head>
<body>
    <div class="contenedor"> <
        <div class="titulo">
            <h1>¿Quieres ser mi Valentine?</h1>
        </div>
        <div class="opciones">
            <p class="pl">No</p>
            <p onclick="dijosi()" class="p2">Si</p>
            <div id="si">
                <h2>Yeiii, te amo mi amor</h2>
            </div>
        </div>
    </div>
</body>
</html>
