<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>Semáforo</title>
</head>
<body>
    <h2 id="texto">Semáforo</h2>
            <main>
              <div>
                      <img id="img" src="IMG/desligado.png" alt="imagem centralizada">
              </div>

              <div id="buttons">
                       <button onclick="document.getElementById('img').src='IMG/vermelho.png'">Vermelho</button>
                       <button  onclick="document.getElementById('img').src='IMG/Amarelo.png'">Amarelo</button>
                       <button  onclick="document.getElementById('img').src='IMG/verde.png'">Verde</button>
                       <button  onclick="document.getElementById('img').src='IMG/desligado.png'">desligado</button>

              </div>
            </main>
</body>
</html>
