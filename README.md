<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>HouseSecurity</title>

  <!-- Ícones -->
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
      color: white;
      padding: 20px 40px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      border-bottom: 2px solid #4facfe;
    }

    header h1 {
      font-size: 24px;
      color: #4facfe;
    }

    nav a {
      color: white;
      margin-left: 20px;
      text-decoration: none;
      font-weight: bold;
      transition: 0.3s;
    }

    nav a:hover {
      color: #4facfe;
    }

    .hero {
      text-align: center;
      padding: 100px 20px;
      background: url('https://images.unsplash.com/photo-1581092334497-4c1c7b2b3b1b') center/cover no-repeat;
      color: white;
    }

    .hero h2 {
      font-size: 42px;
      margin-bottom: 20px;
    }

    .hero p {
      font-size: 18px;
      margin-bottom: 30px;
    }

    .btn {
      background: #4facfe;
      color: white;
      padding: 12px 25px;
      border-radius: 25px;
      text-decoration: none;
      transition: 0.3s;
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
      box-shadow: 0 5px 15px rgba(0,0,0,0.4);
      transition: 0.3s;
      text-align: center;
    }

    .card i {
      font-size: 40px;
      color: #4facfe;
      margin-bottom: 15px;
    }

    .card:hover {
      transform: translateY(-10px);
    }

    .card h3 {
      margin-bottom: 10px;
      color: #4facfe;
    }

    footer {
      text-align: center;
      padding: 20px;
      background: #020617;
      color: #9ca3af;
      margin-top: 40px;
    }

    @media (max-width: 768px) {
      .hero h2 {
        font-size: 28px;
      }

      .services {
        flex-direction: column;
        align-items: center;
      }
    }
  </style>
</head>

<body>

  <header>
    <h1>🔒 HouseSecurity</h1>
    <nav>
      <a href="#">Home</a>
      <a href="#">Serviços</a>
      <a href="#">Contato</a>
    </nav>
  </header>

  <section class="hero">
    <h2>Proteja sua casa com tecnologia inteligente</h2>
    <p>Monitoramento 24h e alarmes modernos para sua tranquilidade.</p>
    <a href="#" class="btn">Solicitar orçamento</a>
  </section>

  <section class="services">

    <div class="card">
      <i class="fas fa-bell"></i>
      <h3>Sistemas de Alarme</h3>
      <p>Alarmes inteligentes com sensores de movimento e abertura.</p>
    </div>

    <div class="card">
      <i class="fas fa-shield-alt"></i>
      <h3>Monitoramento 24h</h3>
      <p>Equipe especializada monitorando sua casa em tempo real.</p>
    </div>

  </section>

  <footer>
    <p>© 2026 HouseSecurity - Sistema de segurança residencial</p>
  </footer>

</body>
</html>
