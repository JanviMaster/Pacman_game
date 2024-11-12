 <h1>Pac-Man Style Arcade Game</h1>
    <p>A simple Pac-Man-inspired arcade game built with Python and Pygame. The objective of the game is to move the player around the board, collect pellets, and avoid or defeat the ghosts.</p>
    <h2>Table of Contents</h2>
    <ul>
        <li><a href="#game-description">Game Description</a></li>
        <li><a href="#features">Features</a></li>
    </ul>
    <h2 id="game-description">Game Description</h2>
    <p>This is a Pac-Man-like game where the player navigates through a maze, eating pellets and power-ups while avoiding ghosts. If a power-up is collected, the player can eat the ghosts temporarily. The game ends when all pellets are eaten (victory) or when the player loses all lives (game over).</p>
    <h2 id="features">Features</h2>
    <ul>
        <li><strong>Player Movement:</strong> Use the arrow keys to navigate through the maze.</li>
        <li><strong>Ghost AI:</strong> Ghosts move around the map, trying to catch the player.</li>
        <li><strong>Power-ups:</strong> Collecting power-ups allows the player to eat ghosts temporarily.</li>
        <li><strong>Win and Lose Conditions:</strong>
            <ul>
                <li>Win: Collect all pellets.</li>
                <li>Lose: Lose all lives by getting caught by the ghosts.</li>
            </ul>
        </li>
        <li><strong>Dynamic Difficulty:</strong> Ghosts get faster and more difficult to avoid as the game progresses.</li>
    </ul>
    <h2 id="installation">Installation</h2>
    <p>To play the game, you need to have Python and Pygame installed.</p>
    <ol>
        <li>Clone this repository:
            <pre><code>git clone https://github.com/JanviMaster/pacman-arcade-game.git<br>cd pacman-arcade-game</code></pre>
        </li>
        <li>Install the required packages:
            <pre><code>pip install pygame</code></pre>
        </li>
        <li>Run the game:
            <pre><code>python pacman_game.py</code></pre>
        </li>
    </ol>
    <h2 id="how-to-play">How to Play</h2>
    <ol>
        <li><strong>Movement</strong>: Use the arrow keys to move your character around the maze.</li>
        <li><strong>Objective</strong>: Collect all the pellets in the maze while avoiding ghosts.</li>
        <li><strong>Power-ups</strong>: Eat power-ups to temporarily gain the ability to defeat ghosts by running into them.</li>
        <li><strong>Lives</strong>: The player has a limited number of lives. Avoid ghosts to prevent losing lives.</li>
    </ol>
    <h2 id="gameplay-mechanics">Gameplay Mechanics</h2>
    <ul>
        <li><strong>Player</strong>: The player can move in four directions. Try to navigate through the maze, avoid the ghosts, and collect pellets.</li>
        <li><strong>Ghost AI</strong>: Ghosts roam the maze and will try to catch the player. Some ghost behaviors include random movement or direct pursuit of the player.</li>
        <li><strong>Power-ups</strong>: Power-ups are special items in the maze. Once collected, they enable the player to eat the ghosts for extra points for a limited time.</li>
        <li><strong>Score</strong>: Points are awarded for collecting pellets and eating ghosts while under the influence of a power-up.</li>
    </ul>
    <h2 id="credits">Credits</h2>
    <p>This project was created as a fun, learning-based exercise in Pygame and Python.</p>
    <h2 id="license">License</h2>
    <p>This project is licensed under the MIT License - see the LICENSE file for details.</p>

