<!DOCTYPE HTML>
<html lang="pt-BR">

<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>SIMPLI</title>
  <!-- Bootstrap CSS -->
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.1.3/dist/css/bootstrap.min.css"
    integrity="sha384-MCw98/SFnGE8fJT3GXwEOngsV7Zt27NXFoaoApmYm81iuXoPkFOJwJ8ERdknLPMO" crossorigin="anonymous" />

  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css">


  <style>
    body {
      background: linear-gradient(135deg, #f5f7fa, #c3cfe2);
    }

    .navbar {
      background-color: #8a05be;
    }

    .navbar-brand {
      font-size: 24px;
      font-weight: bold;
    }

    .nav-link {
      color: #fff;
    }

    .nav-link:hover {
      color: #f0e6ff;
    }

    .jumbotron {
      background-color: transparent;
      text-align: center;
      margin-top: 100px;
    }

    .jumbotron h1 {
      font-size: 40px;
      font-weight: bold;
      margin-bottom: 30px;
    }

    .jumbotron p {
      font-size: 18px;
      margin-bottom: 40px;
    }

    form {
      max-width: 400px;
      margin: 0 auto;
      border: 1px solid #6610f2;
      padding: 20px;
      border-radius: 5px;
    }

    form .form-group label {
      color: #6610f2;
      font-weight: bold;
    }

    form .btn-primary {
      background-color: #6610f2;
      border-color: #6610f2;
    }

    form .btn-primary:hover {
      background-color: #5204a3;
      border-color: #5204a3;
    }

    .container {
      position: relative;
      overflow: hidden;
    }

    .social-media-buttons a.btn-link i {
      color: #6610f2;
    }

    /* Dark mode styles */

    body.dark-mode {
      background: #1c1c1c;
      color: #fff;
    }

    body.dark-mode .navbar {
      background-color: #2c2c2c;
    }

    body.dark-mode .jumbotron {
      color: #fff;
    }

    body.dark-mode form .form-group label {
      color: #fff;
    }

    body.dark-mode form .btn-primary {
      background-color: #bbb;
      border-color: #bbb;
    }

    body.dark-mode form .btn-primary:hover {
      background-color: #999;
      border-color: #999;
    }

    body.dark-mode .social-media-buttons a.btn-link i {
      color: #fff;

  /* Remaining styles */
  
  </style>
</head>

<body>
  <!-- Navigation -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-indigo">
    <a class="navbar-brand" href="#">SIMPLI</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav"
      aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav ml-auto">
        <li class="nav-item active">
          <a class="nav-link" href="#">Início</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Sobre nós</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Sua conta</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Perguntas</a>
        </li>
      </ul>
    </div>
  </nav>

  <!-- Page content -->
<div class="container">
  <div class="jumbotron">
    <h1>Simplifique a sua vida financeira com o Simpli</h1>
    <p>
      O Simpli oferece soluções financeiras modernas e sem complicações.
    </p>
    <a class="btn btn-primary" href="#">Crie sua conta</a>
  </div>
</div>

<!-- Form -->
<form class="border border-indigo p-4">
  <div class="form-group">
    <label for="nome">Nome:</label>
    <input type="text" class="form-control" id="nome" placeholder="Digite seu nome">
  </div>
  <div class="form-group">
    <label for="email">E-mail:</label>
    <input type="email" class="form-control" id="email" placeholder="Digite seu e-mail">
  </div>
  <button type="submit" class="btn btn-primary">Cadastrar!</button>
</form>

<!-- Social media buttons -->
<div class="social-media-buttons fixed-bottom">
  <a href="#" class="btn btn-link"><i class="fab fa-facebook-f"></i></a>
  <a href="#" class="btn btn-link"><i class="fab fa-twitter"></i></a>
  <a href="#" class="btn btn-link"><i class="fab fa-instagram"></i></a>
  <a href="#" class="btn btn-link"><i class="fab fa-linkedin-in"></i></a>
</div>

<button id="dark-mode-toggle" class="btn btn-secondary">
  <i id="dark-mode-icon" class="fas fa-moon"></i>
</button>

<script>
  // Dark mode toggle functionality
  document.getElementById("dark-mode-toggle").addEventListener("click", function() {
    document.body.classList.toggle("dark-mode");
    document.getElementById("dark-mode-icon").classList.toggle("fa-moon");
    document.getElementById("dark-mode-icon").classList.toggle("fa-sun");
  });
</script>


  <!-- Bootstrap JS -->
  <script src="https://code.jquery.com/jquery-3.5.1.min.js"></script>

</body>

</html>
