# meu-arg
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <title>...</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="container">
    <a href="pista1.html" class="misterio">o que se perde entre o silêncio e o sinal?</a>
  </div>
</body>
</html>
body {
  margin: 0;
  padding: 0;
  background-color: #0d0d0d;
  color: #e0e0e0;
  font-family: 'Courier New', Courier, monospace;
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
  overflow: hidden;
}

.container {
  text-align: center;
}

.misterio {
  font-size: 1.5em;
  text-decoration: none;
  color: #e0e0e0;
  animation: glitch 1.5s infinite;
}

@keyframes glitch {
  0% { text-shadow: 2px 2px red; }
  20% { text-shadow: -2px -2px blue; }
  40% { text-shadow: 2px -2px green; }
  60% { text-shadow: -2px 2px purple; }
  80% { text-shadow: 0 0 5px white; }
  100% { text-shadow: none; }
}
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <title>pista 1</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="container">
    <p>“A frequência não é estável. 01101100 01110101 01111010...”</p>
    <p><i>(o que será que isso significa?)</i></p>
  </div>
</body>
</html>
