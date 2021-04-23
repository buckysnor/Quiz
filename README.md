<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>	Quiz</title>
    <link rel="stylesheet" href="modelo.css">
</head>
<br>
    <h1>Qual o melhor personagem?</h1>

    <br>
    <br>
    <br>
    <br>


                
                <div id="Eren" onclick="Clicar()"> Eren</div></br>
                <div id="Mikasa" onclick="Clicou()"> Mikasa</div><br>
                <div id="Armin" onclick="clicar()"  >Armin</div><br>
                <div id="Levi" onclick="clicou()"> Levi</div><br>

                
  


<script>
function Clicar() {
    var a = document.getElementById('Eren')
    a.innerHTML = 'Acertou'
    a.style.background = 'Green'
}
function Clicou() {
    var b = document.getElementById('Mikasa')
    b.innerHTML = 'Errou'
    b.style.background = 'red'
}

function clicar() {

    var c = document.getElementById('Armin')
    c.innerHTML = 'Errou'
    c.style.background = 'red'

}

function clicou() {
    var d = document.getElementById('Levi')
    d.innerHTML = 'Errou'
    d.style.background = 'red'

}




</script>
</body>
</html>
