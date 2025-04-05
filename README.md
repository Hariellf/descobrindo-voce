<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Descobrindo Você - eBook</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: linear-gradient(to bottom, #1a1a1a, #333);
      color: #fff;
    }
    .hero {
      text-align: center;
      padding: 60px 20px;
      background-image: url('capa-do-livro.jpg');
      background-size: cover;
      background-position: center;
      position: relative;
    }
    .hero::before {
      content: "";
      position: absolute;
      top: 0; left: 0; right: 0; bottom: 0;
      background-color: rgba(0, 0, 0, 0.6);
    }
    .hero-content {
      position: relative;
      z-index: 1;
    }
    h1 {
      font-size: 2.5rem;
      margin-bottom: 20px;
    }
    p {
      font-size: 1.2rem;
      margin-bottom: 30px;
    }
    .cta-button {
      background-color: #e63946;
      color: white;
      padding: 15px 30px;
      border: none;
      border-radius: 8px;
      font-size: 1rem;
      cursor: pointer;
      transition: background 0.3s;
    }
    .cta-button:hover {
      background-color: #ff5c7a;
    }
    .section {
      padding: 40px 20px;
      max-width: 800px;
      margin: auto;
    }
    .testimonial {
      background-color: #222;
      padding: 20px;
      border-radius: 8px;
      margin-top: 20px;
    }
  </style>
</head>
<body>

  <section class="hero">
    <div class="hero-content">
      <h1>Descobrindo Você</h1>
      <p>Um mergulho profundo em quem você é de verdade. Liberte-se da confusão e reconecte-se com sua essência.</p>
      <button class="cta-button">Quero minha prévia gratuita</button>
    </div>
  </section>

  <section class="section">
    <h2>O que você encontrará neste eBook?</h2>
    <p>Reflexões intensas, perguntas transformadoras e capítulos que te levam para dentro de si mesmo.</p>
  </section>

  <section class="section">
    <h2>Para quem é esse livro?</h2>
    <p>Para quem se sente perdido, vazio ou com a sensação de estar vivendo no automático. Este livro é uma jornada de reconexão.</p>
  </section>

  <section class="section">
    <h2>Depoimentos</h2>
    <div class="testimonial">
      <p>"Nunca um livro me fez refletir tanto sobre mim. Obrigado por essa obra maravilhosa!" – Joana M.</p>
    </div>
    <div class="testimonial">
      <p>"Transformador! É como se ele falasse exatamente comigo." – Carlos V.</p>
    </div>
  </section>

  <section class="section" style="text-align: center;">
    <button class="cta-button">Adquirir Agora</button>
  </section>

</body>
</html>
