<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8" />
    <title>Hacked by RK7_SEC</title>

    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />

    <meta name="title" content="VandaTheGod" />
    <meta name="description" content="System Compromised by VandaTheGod" />
    <meta name="author" content="VandaTheGod" />
    <meta name="theme-color" content="#000000">

    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Share+Tech+Mono&display=swap" rel="stylesheet">
    
    <link rel="shortcut icon" href="https://files.civicsun.com/Hurt.png" />
    
    <style>
        /* Reset e Configurações Básicas */
        body {
            background-color: #000000;
            color: #fff;
            margin: 0;
            padding: 0;
            font-family: 'Share Tech Mono', monospace;
            height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            overflow: hidden;
            position: relative;
        }

        /* Efeito de Scanline (TV Antiga) no fundo */
        body::before {
            content: " ";
            display: block;
            position: absolute;
            top: 0;
            left: 0;
            bottom: 0;
            right: 0;
            background: linear-gradient(rgba(18, 16, 16, 0) 50%, rgba(0, 0, 0, 0.25) 50%), linear-gradient(90deg, rgba(255, 0, 0, 0.06), rgba(0, 255, 0, 0.02), rgba(0, 0, 255, 0.06));
            z-index: 2;
            background-size: 100% 2px, 3px 100%;
            pointer-events: none;
        }

        /* Imagem Central */
        img.main-logo {
            width: 400px;
            max-width: 90vw;
            margin-bottom: 20px;
            filter: drop-shadow(0 0 10px rgba(255, 0, 0, 0.7));
            animation: fadeIn 2s ease-in-out;
            z-index: 3;
        }

        /* Título Principal */
        h1 {
            color: white;
            font-size: 3.5rem;
            margin: 10px 0;
            text-shadow: 2px 2px 0px #ff0000, -1px -1px 0 #00ffff;
            animation: glitch 1s infinite alternate;
            z-index: 3;
            letter-spacing: 2px;
        }

        /* Subtexto */
        .subtext {
            font-size: 0.7rem;
            color: #cccccc;
            z-index: 3;
            border-right: 2px solid red;
            white-space: nowrap;
            overflow: hidden;
            animation: blinkCursor 0.7s steps(40) infinite normal;
        }

        /* Rodapé / Aviso de clique */
        .click-notice {
            margin-top: 30px;
            font-size: 0.8rem;
            color: #555;
            z-index: 3;
            opacity: 0.7;
        }

        /* Animações Keyframes */
        @keyframes fadeIn {
            from { opacity: 0; transform: scale(0.9); }
            to { opacity: 1; transform: scale(1); }
        }

        @keyframes glitch {
            0% { text-shadow: 2px 2px 0px #ff0000, -1px -1px 0 #00ffff; }
            25% { text-shadow: -2px 2px 0px #ff0000, 1px -1px 0 #00ffff; }
            50% { text-shadow: 2px -2px 0px #ff0000, -1px 1px 0 #00ffff; }
            75% { text-shadow: -2px -2px 0px #ff0000, 1px 1px 0 #00ffff; }
            100% { text-shadow: 2px 2px 0px #ff0000, -1px -1px 0 #00ffff; }
        }

        @keyframes blinkCursor {
            from { border-right-color: red; }
            to { border-right-color: transparent; }
        }

        /* Responsividade para Celular */
        @media (max-width: 600px) {
            h1 { font-size: 2rem; }
            img.main-logo { width: 80%; }
        }
    </style>
</head>
<body>

    <img class="main-logo" src="" alt="" />

    <h1>Hacked By RK7:)</h1>

    <div class="subtext"></div>

    <div class="subtext">Salve para todos(a) corinthiano(a) amo todos vcs;) </div>

    <audio id="player" loop>
        <source src="https://files.civicsun.com/music.mp3" type="audio/mp3">
        Seu navegador não suporta áudio.
    </audio>

    <script>
        // Script para tocar áudio após interação (Burlar bloqueio do Chrome)
        const body = document.body;
        const player = document.getElementById('player');
        const notice = document.querySelector('.click-notice');

        function playAudio() {
            if(player.paused) {
                player.volume = 1.0; // Volume máximo
                player.play().then(() => {
                    console.log('Áudio iniciado.');
                    notice.style.display = 'none'; // Esconde o aviso após clicar
                }).catch((error) => {
                    console.log('Erro ao tocar áudio:', error);
                });
            }
        }

        // Tenta tocar ao clicar ou pressionar qualquer tecla
        body.addEventListener('click', playAudio);
        body.addEventListener('keydown', playAudio);
    </script>

<script defer src="https://static.cloudflareinsights.com/beacon.min.js/vcd15cbe7772f49c399c6a5babf22c1241717689176015" integrity="sha512-ZpsOmlRQV6y907TI0dKBHq9Md29nnaEIPlkf84rnaERnq6zvWvPUqr2ft8M1aS28oN72PdrCzSjY4U6VaAw1EQ==" data-cf-beacon='{"version":"2024.11.0","token":"51f5c4b04a39432893bc62f5b8cb0db3","r":1,"server_timing":{"name":{"cfCacheStatus":true,"cfEdge":true,"cfExtPri":true,"cfL4":true,"cfOrigin":true,"cfSpeedBrain":true},"location_startswith":null}}' crossorigin="anonymous"></script>
</body>
</html>
