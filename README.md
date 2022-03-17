# JogovelhaHTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Joguinho da velhinha</title>
    <link rel="stylesheet" href="./css/velha.css">
</head>
<body>

    <div class="container">

        <header>

            <div class="painel-opcoes esconder">

                <div class="painel-group">
                    <span id="painel-usuario-x-nome"></span>   
                    <span class="pontos">Pontos: <strong id="painel-usuario-x-pontos">0</strong></span>
                </div>

                <div class="painel-group">
                    <span id="painel-usuario-o-nome"></span>
                    <span class="pontos"> Pontos: <strong id="painel-usuario-o-pontos">0</strong></span>
                </div>

                <div class="proximo-jogar">
                    <em><span>Próximo a jogar:</span> <strong id="proximo-jogador"></strong></em>
                </div>

            </div>

            <div class="opcoes-jogo">
                
                <div class="header-group">
                    <label for="usuario-x">Usuario X</label>
                    <input autocomplete="off" id="usuario-x" type="text">
                </div>
    
                <div class="header-group">
                    <label for="usuario-o">Usuario O</label>
                    <input autocomplete="off" id="usuario-o" type="text">
                </div>

                <button id="btn-jogar">Jogar</button>
   
            </div>
  
        </header>
        
        <div class="jogo-velha-1" ></div>
        <div class="jogo-velha-2" ></div>
        <div class="jogo-velha-3" ></div>
        <div class="jogo-velha-4" ></div>
        <div class="jogo-velha-5" ></div>
        <div class="jogo-velha-6" ></div>
        <div class="jogo-velha-7" ></div>
        <div class="jogo-velha-8" ></div>
        <div class="jogo-velha-9" ></div>

        <footer> 
            <em>
                <h4>Desenvolvido por Weberson Rodrigues.</h4>
            </em> 
        </footer>
    </div>

    <script src="./js/velha.js"></script>
</body>
</html>
