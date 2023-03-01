 #
 ejercicio.5
 
 <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Disposiciones de elemento en CSS</title>
    <link rel="stylesheet" href="ejercicio.css">
</head>
<body>
    <div class="Galeria">



        <img class="imagen-galeria" src="imagenes1.jpg" alt="imagen1">
        <img class="imagen-galeria" src="images.jpg" alt="imagen1">
        <img class="imagen-galeria" src="fotos-de-paisajes-lindas.jpg" alt="imagen1">
        <img class="imagen-galeria" src="HD-wallpaper-beautiful-scenery-flowers-nature-sky-lake.jpg" alt="imagen1">
        <img class="imagen-galeria" src="frases_graciosas_para_anunciar_un_embarazo_549_orig.jpg" alt="imagen1"> 
    </div>
</body>
</html>

.Galeria{
    display: flex;
    border: 2px;
    flex-direction: row;
    flex-wrap: wrap;
    gap: 10px;
}
.imagen-galeria{
    width: 300px;
    
}
