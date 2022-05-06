<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <script>
        function operaçao(op){

            console.log (op)
            if (op ==="+"){
                resultado.value = parseInt (v1.value) + parseInt (v2.value)
            } else if (op === "-") {
                resultado.value = parseInt (v1.value) - parseInt (v2.value)
            } else if (op === "*") {
                resultado.value = parseInt (v1.value) * parseInt (v2.value)
            } else if (op === "/") {
                resultado.value = parseInt (v1.value) / parseInt (v2.value)
            } else {
                alert ("Não sei o que fazer!!!")
            }

    }

    </script>
   
   <h1> Calculadora Simples </h1>
   Valor1: <input type="text" id="v1" value="0"><br>
   Valor2: <input type="text" id="v2" value="0"><br>
   <input type="radio" name="op" id="soma"> Soma </br>
 <input type="radio" name="op" id="subtracao" /> Subtrair </br> 
 <input type="radio" name="op" id="multiplicacao"/> Multiplicar</br>
 <input type="radio" name="op" id="divisao"/> Dividir </br>
 <input type="button" value="Executar" onclick="operaçao ()"/> <br>
 Resultado: <input type="text" id="operaçao" id="0" readonly><br>


</body>
</html>
