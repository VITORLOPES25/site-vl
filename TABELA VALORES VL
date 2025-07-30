html_content = """
<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Lavação Personalizada VL</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #0b1e33;
      color: #ffffff;
      margin: 0;
      padding: 0 15px;
    }
    header {
      text-align: center;
      padding: 20px;
    }
    header img {
      max-width: 200px;
      height: auto;
    }
    h2 {
      text-align: center;
      margin-bottom: 20px;
      color: #d0e2ff;
    }
    .tabs {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      margin-bottom: 20px;
    }
    .tab {
      padding: 10px 15px;
      background: #1f3a5f;
      color: #fff;
      margin: 5px;
      border-radius: 5px;
      cursor: pointer;
      transition: background 0.3s;
    }
    .tab.active {
      background: #63a4ff;
      color: #000;
    }
    .content {
      display: none;
      background: #122a45;
      padding: 20px;
      border-radius: 5px;
    }
    .content.active {
      display: block;
    }
    table {
      width: 100%;
      border-collapse: collapse;
      margin-top: 10px;
    }
    th, td {
      padding: 10px;
      border: 1px solid #335;
      text-align: left;
      color: #d0e2ff;
    }
    h3 { color: #a9c8ff; }
    footer {
      text-align: center;
      margin: 30px 0;
      font-size: 14px;
      color: #ccc;
    }
    a { color: #63a4ff; text-decoration: none; }
    a:hover { text-decoration: underline; }
  </style>
</head>
<body>

<header>
  <img src="logo.png" alt="Logo Vitor Lopes">
</header>

<h2>Tabela de Preços</h2>

<div class="tabs">
  <div class="tab active" onclick="showTab(0)">Lavagem Comercial Simples</div>
  <div class="tab" onclick="showTab(1)">Lavagem Técnica Detalhada</div>
  <div class="tab" onclick="showTab(2)">Adicionais</div>
  <div class="tab" onclick="showTab(3)">Polimentos</div>
</div>

<div class="content active">
  <h3>Lavagem Comercial Simples (Externa e Interna)</h3>
  <table>
    <tr><th>Tipo de Veículo</th><th>Preço</th></tr>
    <tr><td>Carro</td><td>R$ 80,00</td></tr>
    <tr><td>SUV</td><td>R$ 100,00</td></tr>
    <tr><td>Camioneta</td><td>R$ 150,00</td></tr>
  </table>
</div>

<div class="content">
  <h3>Lavagem Técnica Detalhada</h3>
  <p>Inclui remoção de chuva ácida dos vidros, cristalização de para-brisa, revitalização de plásticos internos e externos.</p>
  <table>
    <tr><th>Tipo de Veículo</th><th>Preço</th></tr>
    <tr><td>Carro</td><td>R$ 160,00</td></tr>
    <tr><td>SUV</td><td>R$ 180,00</td></tr>
    <tr><td>Camioneta</td><td>R$ 220,00</td></tr>
  </table>
</div>

<div class="content">
  <h3>Adicionais</h3>
  <table>
    <tr><td>Cofre e Motor</td><td>R$ 120,00</td></tr>
    <tr><td>Descontaminação de pintura e aplicação de cera (Blend)</td><td>R$ 80,00</td></tr>
    <tr><td>Cristalização de todos os vidros</td><td>R$ 50,00</td></tr>
    <tr><td>Limpeza de bancos de tecido/couro</td><td>Valores mediante avaliação</td></tr>
    <tr><td>Revitalização de farol (par)</td><td>R$ 100,00</td></tr>
  </table>
</div>

<div class="content">
  <h3>Polimentos</h3>
  <p>Polimento comercial (varia conforme carro/cor/repintura):</p>
  <p><strong>Valores mediante avaliação.</strong></p>
</div>

<footer>
  <p>Siga-nos nas redes sociais:</p>
  <p>
    <a href="https://www.instagram.com/lavacaopersonalizada_vl" target="_blank">Instagram</a> |
    <a href="https://www.facebook.com/VitorLopes" target="_blank">Facebook</a> |
    <a href="https://www.tiktok.com/@VLDetailer" target="_blank">TikTok</a>
  </p>
</footer>

<script>
  function showTab(index) {
    const tabs = document.querySelectorAll('.tab');
    const contents = document.querySelectorAll('.content');
    tabs.forEach((tab, i) => {
      tab.classList.toggle('active', i === index);
      contents[i].classList.toggle('active', i === index);
    });
  }
</script>

</body>
</html>
"""

# Salvar como arquivo HTML
file_path = "/mnt/data/site-vl.html"
with open(file_path, "w", encoding="utf-8") as file:
    file.write(html_content)

file_path
