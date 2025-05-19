<!DOCTYPE html>
<html lang="pt-BR">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Lucas Souza | Linktree</title>
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;600;700&display=swap" rel="stylesheet" />
    <style>
      body {
        margin: 0;
        padding: 0;
        font-family: 'Montserrat', sans-serif;
        background-color: #000;
        color: #fff;
        display: flex;
        flex-direction: column;
        align-items: center;
        min-height: 100vh;
      }
      .logo {
        width: 120px;
        margin: 2rem auto 1rem;
      }
      h1 {
        font-size: 1.5rem;
        font-weight: 700;
        margin: 0.5rem 0;
        color: #fff;
      }
      .bio {
        font-size: 0.95rem;
        text-align: center;
        margin: 0 1rem 1.5rem;
        max-width: 400px;
        line-height: 1.4;
        color: #ddd;
      }
      .link {
        display: flex;
        align-items: center;
        justify-content: center;
        text-decoration: none;
        background-color: #e50914;
        color: #fff;
        padding: 0.9rem 1.2rem;
        border-radius: 8px;
        margin: 0.5rem 0;
        width: 85%;
        max-width: 400px;
        font-weight: 600;
        transition: background 0.3s ease, transform 0.2s ease;
      }
      .link:hover {
        background-color: #ff0a16;
        transform: scale(1.03);
      }
      .link img {
        width: 20px;
        height: 20px;
        margin-right: 0.5rem;
      }
    </style>
  </head>
  <body>
    <img src="logo.png" alt="Logo Casa CPF" class="logo" />
    <h1>Lucas Souza</h1>
    <div class="bio">
      Vocalista da <strong>Casa CPF</strong> e ministro de louvor. <br />
      Single: <em>“Até Que Nada Mais Nos Separe”</em><br />
      Criador do @amissaotaon — inspirando pessoas a pregarem Jesus online.
    </div>
    <a class="link" href="https://open.spotify.com/track/39Dem19lerkk2DGFGSLZgm?si=I9dEmUzCQ2uMxghc3UGT-g" target="_blank">
      <img src="https://cdn-icons-png.flaticon.com/512/174/174872.png" alt="Spotify" />
      Ouça no Spotify
    </a>
    <a class="link" href="https://youtu.be/kmnA8m_Faoc?si=sYQMF_eXJHxeYH7m" target="_blank">
      <img src="https://cdn-icons-png.flaticon.com/512/174/174883.png" alt="YouTube" />
      Ouça no YouTube
    </a>
    <a class="link" href="https://www.instagram.com/amissaotaon" target="_blank">
      <img src="https://cdn-icons-png.flaticon.com/512/2111/2111463.png" alt="Instagram" />
      Perfil @amissaotaon
    </a>
  </body>
</html>
