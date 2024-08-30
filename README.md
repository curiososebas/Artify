<html lang="es">  
<head>  
    <meta charset="utf-8" />  
    <title>Formularios Variados</title>  
    <style>  
        body {  
            font-family: Arial, sans-serif;  
            background-color: #f5f5dc; /* Beige */  
            margin: 0;  
            padding: 0;  
        }  
        .form-container {  
            margin: 20px;  
            padding: 20px;  
            background-color: #ffffff;  
            border: 2px solid;  
        }  
        .form-container:nth-of-type(1) {  
            border-color: #ff6347; /* Tomate */  
        }  
        .form-container:nth-of-type(2) {  
            border-color: #32cd32; /* LimeGreen */  
        }  
        .form-container:nth-of-type(3) {  
            border-color: #1e90ff; /* DodgerBlue */  
        }  
        h3 {  
            border-bottom: 2px solid;  
            padding-bottom: 10px;  
        }  
        .form-container:nth-of-type(1) h3 {  
            border-color: #ff6347; /* Tomate */  
        }  
        .form-container:nth-of-type(2) h3 {  
            border-color: #32cd32; /* LimeGreen */  
        }  
        .form-container:nth-of-type(3) h3 {  
            border-color: #1e90ff; /* DodgerBlue */  
        }  
        label {  
            display: block;  
            margin-bottom: 10px;  
        }  
        fieldset {  
            border: none;  
            margin-top: 10px;  
        }  
    </style>  
</head>  
<body>  
    <div class="form-container">  
        <h3>LAS MEJORES SERIES DE NETFLIX</h3>  
        <form action="#" method="post">  
            <label>Nombre: <input type="text" name="nombre1" placeholder="Escribe tu nombre" autofocus size="30" maxlength="25" required></label><br>  
            <label>Sexo: Hombre <input type="radio" name="sexo1" value="h"></label>  
            <label>Mujer <input type="radio" name="sexo1" value="m"></label><br>  
            <label>Correo electrónico: <input type="email" name="email1" placeholder="Escribe tu correo electronico" required></label>  
            <label>Serie 1: <input type="text" name="serie1" placeholder="Nombre de la serie 1"></label>  
            <label>Serie 2: <input type="text" name="serie2" placeholder="Nombre de la serie 2"></label>  
            <label>Serie 3: <input type="text" name="serie3" placeholder="Nombre de la serie 3"></label>  
            <fieldset>  
                <legend>Mi opinión:</legend>  
                <label><input type="radio" name="opinion1" value="Genial"> Genial</label>  
                <label><input type="radio" name="opinion1" value="Regular"> Regular</label>  
                <label><input type="radio" name="opinion1" value="Pudo haber estado mejor"> Pudo haber estado mejor</label>  
            </fieldset>  
            <label>Acepto las condiciones de privacidad: <input type="checkbox" name="cond1" checked></label>  
            <p>  
                <input type="reset" value="Borrar">  
                <input type="submit" value="Enviar">  
            </p>  
        </form>  
    </div>  
    <div class="form-container">  
         <!doctype html>  
<html lang="es">  
<head>  
    <meta charset="utf-8" />  
    <title>Formularios Variados</title>  
    <style>  
        body {  
            font-family: Arial, sans-serif;  
            background-color: #f5f5dc; /* Beige */  
            margin: 0;  
            padding: 0;  
        }  
        .form-container {  
            margin: 20px;  
            padding: 20px;  
            background-color: #ffffff;  
            border: 2px solid;  
        }  
        .form-container:nth-of-type(1) {  
            border-color: #ff6347; /* Tomate */  
        }  
        .form-container:nth-of-type(2) {  
            border-color: #32cd32; /* LimeGreen */  
        }  
        h3 {  
            border-bottom: 2px solid;  
            padding-bottom: 10px;  
        }  
        label {  
            display: block;  
            margin-bottom: 10px;  
        }  
        fieldset {  
            border: none;  
            margin-top: 10px;  
        }  
    </style>  
</head>  
<body>  
    <div class="form-container">  
        <h3>MIS DEPORTES FAVORITOS</h3>  
        <form action="#" method="post">  
            <label>Nombre: <input type="text" name="nombre2" placeholder="Escribe tu nombre" autofocus size="30" maxlength="25" required></label>  
            <label>Sexo:   
                Hombre <input type="radio" name="sexo2" value="h">  
                Mujer <input type="radio" name="sexo2" value="m">  
            </label>  
            <label>Correo electrónico: <input type="email" name="email2" placeholder="Escribe tu correo electrónico" required></label>  
            <label>Deporte 1: <input type="text" name="deporte1" placeholder="Nombre del deporte 1"></label>  
            <label>Deporte 2: <input type="text" name="deporte2" placeholder="Nombre del deporte 2"></label>  
            <label>Deporte 3: <input type="text" name="deporte3" placeholder="Nombre del deporte 3"></label>  
            <fieldset>  
                <legend>Mi opinión:</legend>  
                <label><input type="radio" name="opinion2" value="Genial"> Genial</label>  
                <label><input type="radio" name="opinion2" value="Regular"> Regular</label>  
                <label><input type="radio" name="opinion2" value="Pudo haber estado mejor"> Pudo haber estado mejor</label>  
            </fieldset>  
            <label>Acepto las condiciones de privacidad: <input type="checkbox" name="cond2" checked></label>  
            <p>  
                <input type="reset" value="Borrar">  
                <input type="submit" value="Enviar">  
            </p>  
        </form>  
    </div>  

    <div class="form-container">  
        <h3>CANCIONES PREFERIDAS</h3>  
        <form action="#" method="post">  
            <label>Nombre: <input type="text" name="nombre3" placeholder="Escribe tu nombre" autofocus size="30" maxlength="25" required></label>  
            <label>Sexo:   
                Hombre <input type="radio" name="sexo3" value="h">  
                Mujer <input type="radio" name="sexo3" value="m">  
            </label>  
            <label>Correo electrónico: <input type="email" name="email3" placeholder="Escribe tu correo electrónico" required></label>  
            <label>Canción 1: <input type="text" name="cancion1" placeholder="Nombre de la canción 1"></label>  
            <label>Canción 2: <input type="text" name="cancion2" placeholder="Nombre de la canción 2"></label>  
            <label>Canción 3: <input type="text" name="cancion3" placeholder="Nombre de la canción 3"></label>  
            <fieldset>  
                <legend>Mi opinión:</legend>  
                <label><input type="radio" name="opinion3" value="Genial"> Genial</label>  
                <label><input type="radio" name="opinion3" value="Regular"> Regular</label>  
                <label><input type="radio" name="opinion3" value="Pudo haber estado mejor"> Pudo haber estado mejor</label>  
            </fieldset>  
            <label>Acepto las condiciones de privacidad: <input type="checkbox" name="cond3" checked></label>  
            <p>  
                <input type="reset" value="Borrar">  
                <input type="submit" value="Enviar">  
            </p>  
        </form>  
    </div>  
</body>  
</html>  
