<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>NEOWA</title>
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Segoe UI', sans-serif; }
        body {
            background: linear-gradient(135deg, #0f172a 0%, #1e293b 100%);
            min-height: 100vh;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            color: white;
        }
        .container { text-align: center; padding: 2rem; max-width: 500px; }
        .logo { font-size: 4rem; margin-bottom: 1rem; }
        h1 { font-size: 3.5rem; font-weight: 700; letter-spacing: 0.3em; margin-bottom: 0.5rem; }
        .slogan { font-size: 1.1rem; color: #94a3b8; margin-bottom: 3rem; letter-spacing: 0.1em; }
        .btn {
            background: rgba(255,255,255,0.1);
            border: 1px solid rgba(255,255,255,0.2);
            color: white;
            padding: 1rem 2.5rem;
            font-size: 1rem;
            border-radius: 50px;
            cursor: pointer;
            transition: all 0.3s ease;
            backdrop-filter: blur(10px);
        }
        .btn:hover { background: rgba(59, 130, 246, 0.4); border-color: rgba(96, 165, 250, 0.6); }
        .footer { position: fixed; bottom: 2rem; font-size: 0.85rem; color: #64748b; }
    </style>
</head>
<body>
    <div class="container">
        <div class="logo">✦</div>
        <h1>NEOWA</h1>
        <p class="slogan">Une porte sur tout ton monde</p>
        <button class="btn" onclick="alert('Bienvenue dans NEOWA !')">Entrer</button>
    </div>
    <div class="footer">NEOWA © 2026 — Tous droits réservés</div>
</body>
</html>
