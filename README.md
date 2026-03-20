<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>HouseSecurity</title>

  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: Arial, sans-serif;
    }

    body {
      background: #0f172a;
      color: #e5e7eb;
    }

    header {
      background: #020617;
      padding: 20px 40px;
      border-bottom: 2px solid #4facfe;
    }

    header h1 {
      color: #4facfe;
    }

    .hero {
      text-align: center;
      padding: 100px 20px;
      background: url('https://images.unsplash.com/photo-1581092334497-4c1c7b2b3b1b') center/cover no-repeat;
      color: white;
    }

    .btn {
      background: #4facfe;
      color: white;
      padding: 12px 25px;
      border-radius: 25px;
      border: none;
      cursor: pointer;
      text-decoration: none;
      display: inline-block;
    }

    .btn:hover {
      background: #00c6ff;
    }

    .services {
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      padding: 60px 20px;
      gap: 20px;
    }

    .card {
      background: #020617;
      padding: 25px;
      width: 280px;
      border-radius: 15px;
      text-align: center;
    }

    .card i {
      font-size: 40px;
      color: #4facfe;
      margin-bottom: 15px;
    }

    .orcamento {
      display: none;
      justify-content: center;
      align-items: center;
      height: 100vh;
    }

    .box {
      background: #020617;
      padding: 40px;
      border-radius: 15px;
      text-align: center;
    }

    .price {
      font-size: 28px;
      margin: 20px 0;
    }

    .contact {
      margin-top: 15px;
    }

    .whatsapp-btn {
      background: #25D366;
      margin-top: 15px;
    }

    .whatsapp-btn:hover {
      background: #1ebe5d;
    }
  </style>
</head>

<body>

  <header>
    <h1>🔒 HouseSecurity</h1>
  </header>

  <!-- HOME -->
  <section id="home">
    <div class="hero">
      <h2>Proteja sua casa com tecnologia inteligente</h2>
      <p>Monitoramento 24h e alarmes modernos para sua tranquilidade.</p>
      <button class="btn" onclick="mostrarOrcamento()">Solicitar orçamento</button>
    </div>

    <section class="services">
      <div class="card">
        <i class="fas fa-bell"></i>
        <h3>Sistemas de Alarme</h3>
        <p>Alarmes inteligentes com sensores de movimento.</p>
      </div>

      <div class="card">
        <i class="fas fa-shield-alt"></i>
        <h3>Monitoramento 24h</h3>
        <p>Segurança em tempo real.</p>
      </div>
    </section>
  </section>

  <!-- ORÇAMENTO -->
  <section id="orcamento" class="orcamento">
    <div class="box">
      <h1>Seu Orçamento</h1>
      <p class="price">💰 R$ 300,00</p>

      <p class="contact">Entre em contato com o Matheus:</p>

      <!-- BOTÃO WHATSAPP -->
      <a href="https://wa.me/5511992267775" target="_blank" class="btn whatsapp-btn">
        <i class="fab fa-whatsapp"></i> Falar no WhatsApp
      </a>

      <br><br>
      <button class="btn" onclick="voltar()">Voltar</button>
    </div>
  </section>

  <script>
    function mostrarOrcamento() {
      document.getElementById("home").style.display = "none";
      document.getElementById("orcamento").style.display = "flex";
    }

    function voltar() {
      document.getElementById("home").style.display = "block";
      document.getElementById("orcamento").style.display = "none";
    }
  </script>

</body>
</html>
