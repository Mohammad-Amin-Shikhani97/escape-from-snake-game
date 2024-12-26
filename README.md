<!DOCTYPE html>
<h1>Escape From Snake Game</h1>

<p>
Escape From Snake Game is a console-based Java program where you navigate a character around a grid, collecting gold and avoiding a hungry snake. Reach the door with gold in hand to win, but beware—the snake moves closer every turn!
</p>

<h2>Features</h2>
<ul>
  <li><strong>Console-based movement:</strong> Use <em>w, a, s, d</em> to move.</li>
  <li><strong>Randomized positions:</strong> Player, snake, gold, and door coordinates are randomized each game.</li>
  <li><strong>Dynamic snake movement:</strong> The snake automatically moves closer to the player’s position.</li>
  <li><strong>Color-coded output:</strong> Player (P), Snake (S), Gold (G), and Door (D) each appear in a unique color.</li>
  <li><strong>Winning condition:</strong> Collect the gold first, then reach the door to escape.</li>
</ul>

<h2>How to Run</h2>
<ol>
  <li><strong>Compile:</strong> In your terminal, navigate to the folder containing
    <code>escapeFromSnakeGame.java</code> and run:
    <pre><code>javac escapeFromSnakeGame.java
</code></pre>
  </li>
  <li><strong>Execute:</strong> 
    <pre><code>java escapeFromSnakeGame
</code></pre>
  </li>
  <li><strong>Gameplay:</strong> 
    <ul>
      <li>Enter <em>w, a, s, d</em> to move up, left, down, or right within the grid.</li>
      <li>Avoid the snake at all costs.</li>
      <li>Pick up the gold (G) before heading to the door (D).</li>
    </ul>
  </li>
</ol>

<h2>Class Overview</h2>
<ul>
  <li><strong>escapeFromSnakeGame.java:</strong> Main class that initializes positions and runs the game loop.</li>
  <li><strong>play(...):</strong> Handles core gameplay logic (e.g., snake/player movement, collisions).</li>
  <li><strong>printResult(...):</strong> Renders the grid with color-coded entities.</li>
  <li><strong>movePlayer(...):</strong> Processes player input for movement.</li>
  <li><strong>moveSnake(...):</strong> Advances the snake’s position toward the player.</li>
</ul>

<h2>References</h2>
<ul>
  <li><a href="https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html" target="_blank">Java AWT Point</a></li>
  <li><a href="https://docs.oracle.com/javase/8/docs/api/java/util/Random.html" target="_blank">Java Random Class</a></li>
  <li><a href="https://docs.oracle.com/javase/8/docs/api/java/util/Scanner.html" target="_blank">Java Scanner Class</a></li>
  <li><a href="https://docs.oracle.com/javase/tutorial/java/" target="_blank">Java Tutorials</a></li>
</ul>

<h2>License</h2>
<p>
You are free to use, modify, and distribute this code for personal or academic purposes.
</p>
