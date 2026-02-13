/index.html
/games/jacksmith.swf
/games/game2.swf
<!DOCTYPE html>
<html>
<head>
  <title>My Game Arcade</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: linear-gradient(to right, #141e30, #243b55);
      color: white;
      text-align: center;
    }

    h1 {
      padding: 30px;
      font-size: 48px;
    }

    .game-container {
      display: flex;
      justify-content: center;
      gap: 30px;
      flex-wrap: wrap;
      padding: 40px;
    }

    .game-card {
      background: #1f2a40;
      padding: 20px;
      border-radius: 15px;
      width: 220px;
      transition: 0.3s;
      box-shadow: 0 0 15px rgba(0,0,0,0.5);
    }

    .game-card:hover {
      transform: scale(1.05);
      box-shadow: 0 0 25px #00f2ff;
    }

    .game-card button {
      margin-top: 15px;
      padding: 10px 20px;
      border: none;
      border-radius: 8px;
      background: #00f2ff;
      color: black;
      font-weight: bold;
      cursor: pointer;
    }

    .game-card button:hover {
      background: #00c3cc;
    }
  </style>
</head>
<body>

  <h1>🎮 My Game Arcade</h1>

  <div class="game-container">

    <div class="game-card">
      <h2>Jacksmith</h2>
      <button onclick="location.href='jacksmith.html'">
        Play
      </button>
    </div>

    <div class="game-card">
      <h2>Game 2</h2>
      <button onclick="location.href='game2.html'">
        Play
      </button>
    </div>

  </div>

</body>
</html>
