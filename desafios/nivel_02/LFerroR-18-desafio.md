<?php
$altura = 1.90;
$peso = 50;

$imc = ($peso/($altura*$altura));
echo("IMC: $imc");
echo"<br>";

if($imc < 18 ) {
        echo ("Abaixo do peso");
}    elseif($imc >= 18.5 && $imc <= 24.9){
        echo("Peso normal");
}    elseif($imc >= 25 && $imc <= 29.9){
            echo("Acima do peso");
    } else{
        echo ("Obsidade");
    }