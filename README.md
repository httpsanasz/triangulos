# triangulos
estrutura condicional de if e if else em php
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="testeriangulo" content="width=device-width, initial-scale=1.0">
    <title><i><b>Qual seu tipo de triângulo?</b></i> </title>
</head>
<body>
    <php?>
        <fieldset class="formulario">
 <strong></br><big>TRIÂNGULOS</big></strong>
<h3>
<p style = "color:blueviolet">
    <section class="container">
        <h1></h1>
        <form action="/" class="form" method="POST">
        </br><label for="nome"><i><small>Quantos lados iguais seu triângulo tem?</small></i></label>
        </br>
        </br><input type="int" id="lados" name="lados">
    </br>
        </br><button type="submit">enviar</button>
        </form>
         </section>
        </p>
        </fieldset>
    </h3>
    </php>
</body>
</html>

------------------------------------------------------

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="testetriangulo" content="width=device-width, initial-scale=1.0">
    <title><b>Triangulos</br></title>
    </head>

    <body>

    <?php

    $lados = null;

    $lados = (int) $_POST ['lados'];

    if ($lados = 3) {
       echo "<h3> O seu triangulo tem $lados lados iguais, e ele é um triângulo equilátero.";
    } elseif ($lados = 2) {
       echo "<h3> O seu triangulo tem $lados lados iguais, e ele é um triângulo isóceles.";
    } elseif ($lados = 0 ){
        echo "<h3> O seu triangulo tem $lados lados iguais, e ele é um triângulo escaleno.";
    }

    ?>
    
</body>
</html>
