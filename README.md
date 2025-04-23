# saida-da-sorte-site
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Saída da Sorte</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background: linear-gradient(to bottom, #111, #222);
      color: #fff;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      min-height: 100vh;
      text-align: center;
      padding: 20px;
    }
    h1 {
      font-size: 2.8rem;
      margin-bottom: 20px;
      animation: fadeIn 2s ease-out;
    }
    p {
      font-size: 1.3rem;
      margin-bottom: 40px;
      max-width: 600px;
      animation: fadeIn 3s ease-out;
    }
    .btn {
      background-color: #e63946;
      color: white;
      border: none;
      padding: 15px 30px;
      font-size: 1rem;
      border-radius: 30px;
      cursor: pointer;
      text-decoration: none;
      box-shadow: 0 0 15px rgba(230, 57, 70, 0.4);
      animation: fadeIn 4s ease-out;
    }
    .btn:hover {
      background-color: #d62839;
    }
    .video-space {
      margin-top: 60px;
      border: 2px dashed #555;
      padding: 40px;
      border-radius: 10px;
      max-width: 600px;
      width: 100%;
      animation: fadeIn 5s ease-out;
    }
    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(30px); }
      to { opacity: 1; transform: translateY(0); }
    }
  </style>
</head>
<body>

  <h1>O vício em jogos destrói vidas em silêncio.</h1>
  <p>Você não está sozinho. Existe uma saída. Estamos aqui para ajudar.</p>
  <a href="#" class="btn">Quero ajuda agora</a>

  <div class="video-space">
    Espaço reservado para o vídeo com frases impactantes.
  </div>

</body>
</html>
