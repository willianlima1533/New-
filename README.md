<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <title>Quantum Browser & Dropshipping</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
  <h1>Projeto Quantum Browser</h1>
  <p>Protótipo para navegação e dropshipping de acessórios de tabacaria.</p>
  <input type="text" id="url" placeholder="Digite uma URL">
  <button onclick="loadURL()">Carregar</button>

  <script>
    function loadURL() {
      const url = document.getElementById('url').value;
      if (url) window.open(url, '_blank');
    }
  </script>
</body>
</html>