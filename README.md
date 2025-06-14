
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>YumMaze - Maze</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <h1>🍭 YumMaze</h1>
    <nav>
      <a href="index.html">Maze</a>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>YumMaze - Game</title>
  <style>
    body {
      font-family: 'Cherry Swash', cursive, sans-serif;
      background: #fff0f5;
      color: #4b0082;
      margin: 0;
      display: flex;
      flex-direction: column;
      align-items: center;
      padding: 20px;
    }
    header {
      background: linear-gradient(to right, #ff66cc, #ffccff);
      padding: 20px;
      width: 100%;
      text-align: center;
      border-bottom: 4px dashed #ff99cc;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
      margin-bottom: 20px;
    }
    nav a {
      margin: 0 15px;
      text-decoration: none;
      color: #4b0082;
      font-weight: bold;
      font-size: 1.2em;
    }
    nav a:hover {
      text-decoration: underline;
      color: #ff3399;
    }
    h1 {
      margin: 0;
      font-size: 2.5em;
      color: #d63384;
    }
    #maze {
      display: grid;
      grid-template-columns: repeat(10, 40px);
      grid-template-rows: repeat(10, 40px);
      gap: 2px;
      user-select: none;
    }
    .cell {
      width: 40px;
      height: 40px;
      background-color: #d9b3ff; /* light purple */
      border-radius: 6px;
      box-sizing: border-box;
      position: relative;
    }
    .wall {
      background-color: #6a0dad; /* dark purple wall */
    }
    .player {
      background-color: #ff66cc; /* pink player */
      border-radius: 8px;
      box-shadow: 0 0 10px #ff99cc;
      transition: background-color 0.3s;
    }
    .goal {
      background-color: #32cd32; /* lime green goal */
      border-radius: 6px;
      box-shadow: 0 0 10px #90ee90;
    }
    #instructions {
      margin-top: 20px;
      font-size: 1.1em;
      max-width: 400px;
      text-align: center;
      color: #4b0082;
    }
    #win-message {
      margin-top: 20px;
      font-size: 1.5em;
      color: #32cd32;
      font-weight: bold;
      display: none;
    }
    button#restart {
      margin-top: 15px;
      padding: 10px 20px;
      font-size: 1em;
      background: #ff66cc;
      border: none;
      border-radius: 8px;
      color: white;
      cursor: pointer;
      box-shadow: 0 4px 6px rgba(255,102,204,0.5);
      transition: background 0.3s;
    }
    button#restart:hover {
      background: #ff3399;
    }
  </style>
</head>
<body>
  <header>
    <h1>🍭 YumMaze</h1>
    <nav>
      <a href="index.html">Maze</a>
      <a href="game.html">Game</a>
      <a href="materials.html">Materials</a>
    </nav>
  <main>
    <h2>Maze</h2>
    <p>Welcome to the maze! Navigate your way through our sweet candy-themed puzzle adventure!</p>
  </main>

<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>YumMaze - Game</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <h1>🍭 YumMaze</h1>
  
  </header>

  <main>
    <h2>Game</h2>
    <p>Play fun mini-games and puzzles! Sweet rewards await!</p>
  </main>
</body>
</html>

<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>YumMaze - Materials</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <h1>🍭 YumMaze</h1>
    <nav>
      <a href="index.html">Maze</a>
     
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>YumMaze - Game</title>
  <style>
    body {
      font-family: 'Cherry Swash', cursive, sans-serif;
      background: #fff0f5;
      color: #4b0082;
      margin: 0;
      display: flex;
      flex-direction: column;
      align-items: center;
      padding: 20px;
    }
    header {
      background: linear-gradient(to right, #ff66cc, #ffccff);
      padding: 20px;
      width: 100%;
      text-align: center;
      border-bottom: 4px dashed #ff99cc;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
      margin-bottom: 20px;
    }
    nav a {
      margin: 0 15px;
      text-decoration: none;
      color: #4b0082;
      font-weight: bold;
      font-size: 1.2em;
    }
    nav a:hover {
      text-decoration: underline;
      color: #ff3399;
    }
    h1 {
      margin: 0;
      font-size: 2.5em;
      color: #d63384;
    }
    #maze {
      display: grid;
      grid-template-columns: repeat(10, 40px);
      grid-template-rows: repeat(10, 40px);
      gap: 2px;
      user-select: none;
    }
    .cell {
      width: 40px;
      height: 40px;
      background-color: #d9b3ff; /* light purple */
      border-radius: 6px;
      box-sizing: border-box;
      position: relative;
    }
    .wall {
      background-color: #6a0dad; /* dark purple wall */
    }
    .player {
      background-color: #ff66cc; /* pink player */
      border-radius: 8px;
      box-shadow: 0 0 10px #ff99cc;
      transition: background-color 0.3s;
    }
    .goal {
      background-color: #32cd32; /* lime green goal */
      border-radius: 6px;
      box-shadow: 0 0 10px #90ee90;
    }
    #instructions {
      margin-top: 20px;
      font-size: 1.1em;
      max-width: 400px;
      text-align: center;
      color: #4b0082;
    }
    #win-message {
      margin-top: 20px;
      font-size: 1.5em;
      color: #32cd32;
      font-weight: bold;
      display: none;
    }
    button#restart {
      margin-top: 15px;
      padding: 10px 20px;
      font-size: 1em;
      background: #ff66cc;
      border: none;
      border-radius: 8px;
      color: white;
      cursor: pointer;
      box-shadow: 0 4px 6px rgba(255,102,204,0.5);
      transition: background 0.3s;
    }
    button#restart:hover {
      background: #ff3399;
    }
  </style>
</head>
<body>
  <header>
    <h1></h1>
  </header>

  <main>
    <h2>Maze Game</h2>
    <div id="maze" aria-label="Maze game grid" role="grid"></div>
    <div id="instructions">
      Use arrow keys (← ↑ → ↓) to move the pink candy block to the green goal.
    </div>
    <div id="win-message">🎉 You won! Sweet job! 🍬</div>
    <button id="restart" aria-label="Restart maze game">Restart Game</button>
  </main>

  <script>
    const mazeElement = document.getElementById('maze');
    const winMessage = document.getElementById('win-message');
    const restartBtn = document.getElementById('restart');

    // Maze layout:
    // 0 = open path, 1 = wall, 2 = goal
    // 10x10 grid
    const mazeLayout = [
      [0,0,0,1,0,0,0,1,0,2],
      [1,1,0,1,0,1,0,1,0,1],
      [0,0,0,0,0,1,0,0,0,1],
      [0,1,1,1,0,1,1,1,0,1],
      [0,1,0,0,0,0,0,1,0,0],
      [0,1,0,1,1,1,0,1,1,0],
      [0,0,0,0,0,0,0,0,1,0],
      [1,1,1,1,1,1,1,0,1,0],
      [0,0,0,0,0,0,0,0,1,0],
      [0,1,1,1,1,1,1,1,1,0],
    ];

    // Player starting position
    let playerPos = { row: 0, col: 0 };

    // Create maze cells
    function createMaze() {
      mazeElement.innerHTML = '';
      for (let r=0; r<mazeLayout.length; r++) {
        for (let c=0; c<mazeLayout[r].length; c++) {
          const cell = document.createElement('div');
          cell.classList.add('cell');
          if (mazeLayout[r][c] === 1) cell.classList.add('wall');
          if (mazeLayout[r][c] === 2) cell.classList.add('goal');
          cell.setAttribute('data-row', r);
          cell.setAttribute('data-col', c);
          mazeElement.appendChild(cell);
        }
      }
    }

    // Draw player position
    function drawPlayer() {
      // Remove old player
      document.querySelectorAll('.player').forEach(el => el.classList.remove('player'));

      // Add player to new position
      const cells = document.querySelectorAll('.cell');
      for (const cell of cells) {
        const r = parseInt(cell.getAttribute('data-row'));
        const c = parseInt(cell.getAttribute('data-col'));
        if (r === playerPos.row && c === playerPos.col) {
          cell.classList.add('player');
          break;
        }
      }
    }

    // Check if move is valid
    function canMoveTo(row, col) {
      if (row < 0 || row >= mazeLayout.length) return false;
      if (col < 0 || col >= mazeLayout[0].length) return false;
      if (mazeLayout[row][col] === 1) return false;
      return true;
    }

    // Check if player is on goal
    function checkWin() {
      if (mazeLayout[playerPos.row][playerPos.col] === 2) {
        winMessage.style.display = 'block';
      }
    }

    // Move player based on key pressed
    function movePlayer(e) {
      if (winMessage.style.display === 'block') return; // stop if won

      let newRow = playerPos.row;
      let newCol = playerPos.col;

      switch(e.key) {
        case 'ArrowUp':
          newRow--;
          break;
        case 'ArrowDown':
          newRow++;
          break;
        case 'ArrowLeft':
          newCol--;
          break;
        case 'ArrowRight':
          newCol++;
          break;
        default:
          return; // ignore other keys
      }

      if (canMoveTo(newRow, newCol)) {
        playerPos = { row: newRow, col: newCol };
        drawPlayer();
        checkWin();
      }
    }

    // Restart game
    function restartGame() {
      playerPos = { row: 0, col: 0 };
      drawPlayer();
      winMessage.style.display = 'none';
    }

    // Init
    createMaze();
    drawPlayer();

    // Event listeners
    window.addEventListener('keydown', movePlayer);
    restartBtn.addEventListener('click', restartGame);
  </script>
</body>
</html>
">Game</a>
      <a href="materials.html">Materials</a>
    </nav>
  </header>

  <main>
    <h2>Materials</h2>
    <p>To bring YumMaze to life, we used a playful mix of strong and shiny materials. The main structure of the maze is crafted from <strong>timber</strong>, giving it a sturdy base that holds everything together. To add a touch of fun and visibility, we used clear <strong>perspex</strong> panels—so you can peek into the maze while solving it!</p>
  </main>
</body>
</html>



I'm so skibidi toilet sigma gyatt ohio rizz
