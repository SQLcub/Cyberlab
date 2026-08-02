<!DOCTYPE html>
<html lang="tr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>CyberLab | Etik Siber Güvenlik</title>

  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: Arial, sans-serif;
      color: #f4f4f5;
      background: #080b12;
    }

    header {
      display: flex;
      align-items: center;
      justify-content: space-between;
      padding: 20px 8%;
      border-bottom: 1px solid #1d2939;
      background: #0d111a;
    }

    .logo {
      color: #39ff88;
      font-size: 24px;
      font-weight: bold;
    }

    nav a {
      color: #cbd5e1;
      text-decoration: none;
      margin-left: 24px;
    }

    nav a:hover {
      color: #39ff88;
    }

    .hero {
      display: grid;
      grid-template-columns: 1fr 1fr;
      align-items: center;
      gap: 40px;
      min-height: 75vh;
      padding: 70px 8%;
    }

    .hero h1 {
      font-size: clamp(42px, 6vw, 76px);
      line-height: 1.05;
      margin-bottom: 24px;
    }

    .hero h1 span {
      color: #39ff88;
    }

    .hero p {
      max-width: 560px;
      color: #94a3b8;
      font-size: 18px;
      line-height: 1.7;
      margin-bottom: 30px;
    }

    .buttons {
      display: flex;
      gap: 14px;
    }

    .button {
      display: inline-block;
      padding: 14px 22px;
      border-radius: 8px;
      color: #06100a;
      background: #39ff88;
      font-weight: bold;
      text-decoration: none;
    }

    .button.secondary {
      color: #f4f4f5;
      background: #151d2b;
      border: 1px solid #2a3a50;
    }

    .terminal {
      padding: 24px;
      border: 1px solid #26364d;
      border-radius: 14px;
      background: #0e1622;
      box-shadow: 0 0 35px rgba(57, 255, 136, 0.12);
    }

    .terminal-bar {
      color: #64748b;
      margin-bottom: 22px;
    }

    .terminal p {
      color: #39ff88;
      font-family: monospace;
      line-height: 2;
    }

    .features {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 20px;
      padding: 30px 8% 80px;
    }

    .card {
      padding: 26px;
      border: 1px solid #1f3045;
      border-radius: 12px;
      background: #0d141f;
    }

    .card h3 {
      margin-bottom: 12px;
      color: #39ff88;
    }

    .card p {
      color: #94a3b8;
      line-height: 1.6;
    }

    footer {
      padding: 25px;
      color: #64748b;
      text-align: center;
      border-top: 1px solid #1d2939;
    }

    @media (max-width: 800px) {
      header {
        flex-direction: column;
        gap: 16px;
      }

      nav a {
        margin: 0 8px;
      }

      .hero {
        grid-template-columns: 1fr;
        padding-top: 50px;
      }

      .features {
        grid-template-columns: 1fr;
      }
    }
  </style>
</head>

<body>
  <header>
    <div class="logo">CyberLab</div>

    <nav>
      <a href="#dersler">Dersler</a>
      <a href="#ctf">CTF</a>
      <a href="#hakkinda">Hakkında</a>
    </nav>
  </header>

  <main>
    <section class="hero">
      <div>
        <h1>Siber güvenliği <span>etik</span> öğren.</h1>

        <p>
          Güvenli laboratuvarlar, uygulamalı dersler ve yasal CTF görevleriyle
          siber güvenlik becerilerini geliştir.
        </p>

        <div class="buttons">
          <a class="button" href="#dersler">Derslere Başla</a>
          <a class="button secondary" href="#ctf">CTF Görevleri</a>
        </div>
      </div>

      <div class="terminal">
        <div class="terminal-bar">cyberlab@student:~$</div>
        <p>> Sistem başlatılıyor...</p>
        <p>> Güvenli laboratuvar hazır.</p>
        <p>> Öğrenme modu aktif.</p>
        <p>> Hoş geldin, hacker.</p>
      </div>
    </section>

    <section class="features" id="dersler">
      <article class="card">
        <h3>Uygulamalı Dersler</h3>
        <p>Linux, ağ güvenliği, web güvenliği ve savunma tekniklerini öğren.</p>
      </article>

      <article class="card" id="ctf">
        <h3>Güvenli CTF</h3>
        <p>Yalnızca izole ve izinli ortamlarda problem çözme becerini geliştir.</p>
      </article>

      <article class="card" id="hakkinda">
        <h3>İlerleme Sistemi</h3>
        <p>Puan kazan, rozet topla ve liderlik tablosunda ilerle.</p>
      </article>
    </section>
  </main>

  <footer>
    © 2026 CyberLab — Yalnızca yasal ve izinli güvenlik çalışmaları için.
  </footer>
</body>
</html>

