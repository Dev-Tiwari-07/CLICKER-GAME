
<!DOCTYPE html>
<html>
<head>
  <title>My Clicker Game</title>

  <style>
    body {
      font-family: Arial;
      text-align: center;
      background: #0f0f0f;
      color: white;
      margin-top: 100px;
    }

    h1 {
      color: #00ffcc;
    }

    #score {
      font-size: 50px;
      margin: 20px;
    }

    button {
      padding: 20px 40px;
      font-size: 22px;
      border: none;
      border-radius: 10px;
      cursor: pointer;
      background: #00ffcc;
      color: black;
    }

    button:hover {
      background: #00ccaa;
    }
  </style>
</head>

<body>

  <h1>🔥 Clicker Game</h1>

  <div id="score">0</div>

  <button onclick="addScore()">CLICK ME</button>

  <script>
    let score = 0;

    function addScore() {
      score++;
      document.getElementById("score").innerText = score;
    }
  </script>

</body>
</html>