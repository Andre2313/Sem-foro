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

body{
    background-image: url('IMG/estrada-de-asfalto-vazia-para-a-cidade-moderna_9083-2791.avif');
    background-size: cover;           /* A imagem cobre o ecrã */
    background-repeat: no-repeat;     /* A imagem não se repete */
    background-position: center;      /* A imagem está centrada */
    background-attachment: fixed;     /* A imagem permanece fixa ao fazer scroll */
    background-color: #f0f0f0; 

     main{
        display: flex;
        height: 100vh;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        gap: 5vh;
     }

    button {
               width: 80px;
               cursor: pointer;
    }

    *{
        margin: 0;
        padding: 0;
        box-sizing: border-box;
    }
   
    h2{
        display: flex;                 /* Usa Flexbox para centralizar o H1 dentro da caixa */
        justify-content: center;        /* Centraliza horizontalmente o conteúdo */
        align-items: center;            /* Centraliza verticalmente o conteúdo */
        padding: 10px 20px;             /* Espaçamento ao redor do H1 */
        background-color: #f0f0f0;      /* Cor de fundo da caixa */
        border: 1px solid #ccc;         /* Borda da caixa */
        border-radius: 8px;             /* Bordas arredondadas */
        position: absolute;             /* Posiciona a caixa no topo */
        top: 20px;                      /* Ajusta a distância da caixa em relação ao topo */
        left: 50%;                      /* Centraliza horizontalmente */
        transform: translateX(-50%); 
    }


    
}
