<!DOCTYPE html>
<html lang="pt-br">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>CyberHex Technologies</title>

<style>
    /* ----------- ESTILO GERAL ----------- */
    body {
        margin: 0;
        padding: 0;
        font-family: "Courier New", monospace;
        background: #000;
        color: #0aff9d;
        overflow-x: hidden;
    }

    /* Efeito de linhas da tela */
    body::before {
        content: "";
        position: fixed;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
        pointer-events: none;
        background: repeating-linear-gradient(
            to bottom,
            rgba(0, 255, 150, 0.05) 0px,
            rgba(0, 255, 150, 0.05) 1px,
            transparent 2px,
            transparent 3px
        );
        z-index: 999;
    }

    /* ----------- ASCII + NEON ----------- */
    .ascii-container {
        text-align: center;
        white-space: pre;
        font-size: 12px;
        margin-top: 60px;
        color: #0aff9d;
        text-shadow: 0 0 10px #0aff9d, 0 0 20px #00ffaa;
        animation: pulse 2s infinite alternate;
    }

    @keyframes pulse {
        0% { text-shadow: 0 0 5px #0aff9d; }
        100% { text-shadow: 0 0 25px #00ffaa; }
    }

    /* ----------- BANNERS ANIMADOS ----------- */
    .banner {
        width: 100%;
        padding: 15px;
        text-align: center;
        background: linear-gradient(90deg, transparent, #0aff9d22, transparent);
        color: #00ffcc;
        font-size: 18px;
        letter-spacing: 2px;
        margin-top: 40px;
        animation: slide 3s linear infinite;
    }

    @keyframes slide {
        0% { background-position: -200px; }
        100% { background-position: 200px; }
    }

    /* ----------- DESCRIÇÃO / CONTEÚDO ----------- */
    .content {
        width: 85%;
        max-width: 900px;
        margin: 40px auto;
        padding: 20px;
        border: 1px solid #0aff9d55;
        border-radius: 10px;
        background: #0aff9d05;
        backdrop-filter: blur(3px);
        box-shadow: 0 0 20px #0aff9d33;
        animation: fadeIn 1s ease;
    }

    @keyframes fadeIn {
        from { opacity: 0; transform: translateY(30px); }
        to { opacity: 1; transform: translateY(0); }
    }

    /* ----------- BOTÕES ----------- */
    .btn {
        display: inline-block;
        margin: 10px;
        padding: 12px 25px;
        border: 2px solid #0aff9d;
        color: #0aff9d;
        text-decoration: none;
        font-size: 18px;
        border-radius: 8px;
        transition: 0.3s;
        text-shadow: 0 0 10px #00ffaa;
    }

    .btn:hover {
        background: #0aff9d;
        color: #000;
        box-shadow: 0 0 20px #0aff9d;
    }

</style>
</head>
<body>

<!-- ------------------- BANNER ANIMADO ------------------- -->
<div class="banner">▂▃▅▆▇█ CYBERHEX TECHNOLOGIES — SECURITY IS OUR DOMAIN █▇▆▅▃▂</div>

<!-- ------------------- ASCII ART ------------------- -->
<div class="ascii-container">
  ____     _               _   _                 _           
 / ___|___| |__   ___  ___| |_| |__   ___   ___ | | ___  ___ 
| |   / _ \ '_ \ / _ \/ __| __| '_ \ / _ \ / _ \| |/ _ \/ __|
| |__|  __/ | | |  __/\__ \ |_| | | | (_) | (_) | |  __/\__ \
 \____\___|_| |_|\___||___/\__|_| |_|\___/ \___/|_|\___||___/
</div>

<!-- ------------------- DESCRIÇÃO ------------------- -->
<div class="content">
    <h2>🔐 Quem Somos</h2>
    <p>
        A <strong>CyberHex Technologies</strong> é especializada em Segurança da Informação, TI,
        infraestrutura, testes de invasão, hardening, análise de vulnerabilidades e soluções
        avançadas de proteção para empresas.
    </p>

    <h2>⚡ O que Fazemos</h2>
    <ul>
        <li>• Pentest Profissional</li>
        <li>• Consultoria em Segurança</li>
        <li>• Análise e Mitigação de Vulnerabilidades</li>
        <li>• Desenvolvimento de Sistemas Seguros</li>
        <li>• Monitoramento e Resposta a Incidentes</li>
        <li>• Arquitetura e Redes</li>
    </ul>

    <h2>🛰 Contato</h2>
    <a class="btn" href="#">GitHub</a>
    <a class="btn" href="#">Portfólio</a>
    <a class="btn" href="#">WhatsApp</a>
</div>

<!-- ------------------- BANNER INFERIOR ------------------- -->
<div class="banner">▂▃▅▆▇█ SYSTEM ONLINE — ACCESS GRANTED █▇▆▅▃▂</div>

</body>
</html>
