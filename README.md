<div style="text-align: left;">
<html>
    <head></head>
        <body> 
        <h1> An overview of all maze company</h1>
            <h2>The maze is constructed using wooden timber and perspex, combining durability with a modern aesthetic. The timber forms the sturdy framework and structural base, offering a natural, tactile feel. Perspex panels are used for clear barriers or viewing windows, adding a sleek, transparent element that enhances visibility while maintaining strength and safety. Together, these materials create a visually appealing and robust design suitable for interactive play and display.</h2>
        <h1> Check out our brand new maze from <strong>YumMaze</strong></h1>
            <h2> Take a look at our newest design the <em>lolly crush</em></h2>
        <h1>Fun mini maze game</h1>
            <h2>Play this mini game while waitning for your order!<br>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>YumMaze Game</title>
  <style>
    body {
      font-family: 'Comic Sans MS', cursive;
      background-color: #fff0f5;
      text-align: center;
      margin: 0;
    }
    header {
      background: linear-gradient(to right, #ff66cc, #ffccff);
      padding: 20px;
    }
    h1 {
      color: #d63384;
    }
    #maze {
      display: grid;
      grid-template-columns: repeat(10, 40px);
      grid-template-rows: repeat(10, 40px);
      margin: 20px auto;
      gap: 2px;
      width: fit-content;
    }
    .cell {
      width: 40px;
      height: 40px;
      background-color: #ffe6f0;
      border-radius: 4px;
    }
    .wall {
      background-color: #cc66cc;
    }
    .goal {
      background-color: #66ff66;
    }
    .player {
      background-color: #ff3399;
      box-shadow: 0 0 10px #ff99cc;
    }
    #message {
      font-size: 1.5em;
      color: green;
      display: none;
    }
  </style>
</head>
<body>
  <header>
    <h1>🍬 YumMaze Game</h1>
    <p>Use arrow keys to reach the green goal!</p>
  </header>
  <div id="maze"></div>
  <div id="message">🎉 You did it! 🍭</div>

  <script>
    const mazeLayout = [
      [0,0,1,1,1,0,0,0,0,0],
      [1,0,0,0,1,0,1,1,1,0],
      [1,1,1,0,1,0,1,0,1,0],
      [0,0,0,0,0,0,1,0,1,0],
      [0,1,1,1,1,1,1,0,1,0],
      [0,0,0,0,0,0,0,0,1,0],
      [1,1,1,1,1,1,1,0,1,0],
      [0,0,0,0,0,0,1,0,1,0],
      [0,1,1,1,1,0,1,0,1,0],
      [0,0,0,0,1,0,0,0,1,2], // 2 = goal
    ];

    const maze = document.getElementById('maze');
    const message = document.getElementById('message');
    const numRows = mazeLayout.length;
    const numCols = mazeLayout[0].length;
    let playerRow = 0;
    let playerCol = 0;

    function drawMaze() {
      maze.innerHTML = '';
      for (let r = 0; r < numRows; r++) {
        for (let c = 0; c < numCols; c++) {
          const cell = document.createElement('div');
          cell.classList.add('cell');
          if (mazeLayout[r][c] === 1) cell.classList.add('wall');
          if (mazeLayout[r][c] === 2) cell.classList.add('goal');
          if (r === playerRow && c === playerCol) cell.classList.add('player');
          maze.appendChild(cell);
        }
      }
    }

    function movePlayer(rowOffset, colOffset) {
      const newRow = playerRow + rowOffset;
      const newCol = playerCol + colOffset;

      if (
        newRow >= 0 && newRow < numRows &&
        newCol >= 0 && newCol < numCols &&
        mazeLayout[newRow][newCol] !== 1
      ) {
        playerRow = newRow;
        playerCol = newCol;
        drawMaze();

        if (mazeLayout[playerRow][playerCol] === 2) {
          message.style.display = 'block';
        }
      }
    }

    document.addEventListener('keydown', (e) => {
      if (e.key === 'ArrowUp') movePlayer(-1, 0);
      else if (e.key === 'ArrowDown') movePlayer(1, 0);
      else if (e.key === 'ArrowLeft') movePlayer(0, -1);
      else if (e.key === 'ArrowRight') movePlayer(0, 1);
    });

    drawMaze();
  </script>
</body>
</html>
            </h2>
    <h1> The materials we have used for our mazes </h1>
        <h2>The maze is constructed using wooden timber and perspex, combining durability with a modern aesthetic. The timber forms the sturdy framework and structural base, offering a natural, tactile feel. Perspex panels are used for clear barriers or viewing windows, adding a sleek, transparent element that enhances visibility while maintaining strength and safety. Together, these materials create a visually appealing and robust design suitable for interactive play and display.</h2>
    <h1>YumMaze around the world </h1>
        <h2>My maze has been published and shared all around the world, reaching people from different countries and cultures. What started as a simple idea has now become a global experience, with players everywhere enjoying the challenge and creativity behind it. From schools and exhibitions to websites and social media, the maze has gained attention for its unique design and fun gameplay. It’s exciting to know that something I created is being explored by people across the globe, inspiring curiosity and imagination wherever it goes.</h2>
        </body>

        



    
</html>
