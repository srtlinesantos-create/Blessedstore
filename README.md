<!doctype html>
<html lang="pt-br">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Blessed Store | Link Oficial</title>

  <style>
    :root{
      --bg1:#ffb6df;
      --bg2:#ff66c4;
      --bg3:#ff2aa6;
      --card: rgba(255,255,255,.18);
      --stroke: rgba(255,255,255,.32);
      --text:#ffffff;
      --muted: rgba(255,255,255,.9);
      --shadow: rgba(0,0,0,.25);
    }

    *{ box-sizing:border-box; }

    body{
      margin:0;
      min-height:100vh;
      font-family: system-ui,-apple-system,Segoe UI,Roboto,Arial;
      color: var(--text);
      background:
        radial-gradient(900px 500px at 50% 0%, rgba(255,255,255,.30), transparent 60%),
        linear-gradient(135deg, var(--bg1), var(--bg2) 45%, var(--bg3));
      display:flex;
      align-items:center;
      justify-content:center;
      padding: 24px;
    }

    .wrap{ width:100%; max-width:420px; }

    .card{
      background: var(--card);
      border: 1px solid var(--stroke);
      border-radius: 22px;
      padding: 22px;
      box-shadow: 0 16px 38px var(--shadow);
      backdrop-filter: blur(10px);
    }

    .top{
      display:flex;
      align-items:center;
      gap:14px;
      margin-bottom: 14px;
    }

    .logo{
      width:64px;
      height:64px;
      border-radius: 18px;
      overflow:hidden;
      border:1px solid rgba(255,255,255,.55);
      box-shadow: 0 10px 24px rgba(0,0,0,.18);
    }

    .logo img{
      width:100%;
      height:100%;
      object-fit:cover;
    }

    h1{
      margin:0;
      font-size:20px;
    }

    .subtitle{
      margin-top:6px;
      font-size:13px;
      color:var(--muted);
    }

    .btns{
      display:flex;
      flex-direction:column;
      gap:10px;
      margin-top:16px;
    }

    a.btn{
      text-decoration:none;
      display:flex;
      justify-content:space-between;
      align-items:center;
      padding:14px;
      border-radius:16px;
      background:rgba(255,255,255,.16);
      border:1px solid rgba(255,255,255,.28);
      color:var(--text);
      font-weight:600;
      transition:.15s;
    }

    a.btn:hover{
      transform:translateY(-2px);
      background:rgba(255,255,255,.25);
    }

    .primary{
      background:white;
      color:#c0166f;
      font-weight:700;
    }

    .pill{
      font-size:12px;
      padding:5px 10px;
      border-radius:999px;
      background:rgba(255,255,255,.28);
    }

    .footer{
      margin-top:16px;
      text-align:center;
      font-size:12px;
      color:var(--muted);
    }
  </style>
</head>

<body>
  <main class="wrap">
    <section class="card">

      <div class="top">
        <div class="logo">
          <img src="logo.jpg" alt="Blessed Store">
        </div>
        <div>
          <h1>Blessed Store</h1>
          <div class="subtitle">Achadinhos incríveis 💖 • Enviamos para todo Brasil</div>
        </div>
      </div>

      <div class="btns">

        <a class="btn primary" target="_blank"
        href="https://wa.me/5511942770734?text=Ol%C3%A1%20vim%20pela%20Blessed%20Store%20e%20quero%20mais%20informa%C3%A7%C3%B5es%20%F0%9F%98%8A">
          💬 Falar no WhatsApp
          <span class="pill">Atendimento rápido</span>
        </a>

        <a class="btn" target="_blank"
        href="https://collshp.com/alinee031099542?view=storefront">
          🛒 Loja na Shopee
          <span class="pill">Ver produtos</span>
        </a>

        <a class="btn" target="_blank"
        href="https://www.instagram.com/alineblessedstore">
          📸 Instagram
          <span class="pill">@alineblessedstore</span>
        </a>

        <a class="btn" target="_blank"
        href="https://www.tiktok.com/@alineblessedstore">
          🎵 TikTok
          <span class="pill">@alineblessedstore</span>
        </a>

      </div>

      <div class="footer">
        📦 Envio rápido • 💳 Pix & Cartão • 💖 Obrigada por apoiar a Blessed Store
      </div>

    </section>
  </main>
</body>
</html>
