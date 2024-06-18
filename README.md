<h1>Tic-Tac-Toe: Human vs Computer (AI)</h1>

<p>A simple implementation of the classic Tic-Tac-Toe game where the human player competes against an AI opponent.</p>

<p>This Python program allows you to play Tic-Tac-Toe against an AI opponent that utilizes the minimax algorithm with alpha-beta pruning to determine its moves. The game is played on a 3x3 board, and the player takes turns with the AI to place their respective symbols (X and O) on the board. The game ends when either the human or the AI player gets three symbols in a row (horizontally, vertically, or diagonally), or when the board is filled with no winner (a tie).</p>

<h2>Algorithm: Minimax with Alpha-Beta Pruning</h2>

<p>The AI opponent in this game uses the minimax algorithm with alpha-beta pruning to determine its optimal moves. Minimax is a recursive algorithm that assumes both players play optimally, and it explores all possible future game states to determine the best move.</p>

<p>Alpha-beta pruning is an optimization technique used in conjunction with the minimax algorithm to reduce the number of nodes that need to be evaluated. It involves keeping track of the best move found so far for each player and using this information to prune branches of the game tree that cannot possibly influence the final decision.</p>

<p>The combination of minimax and alpha-beta pruning allows the AI to make intelligent decisions and play optimally against the human player.</p>

<h2>How to Play</h2>

<ol>
  <li>Run the Python script.</li>
  <li>The game board will be displayed, and you will be prompted to enter your move by specifying the row and column indices (e.g., <code>0 1</code> for the second column in the first row).</li>
  <li>After you make your move, the AI will calculate its next move based on the minimax algorithm with alpha-beta pruning.</li>
  <li>The game will continue until either you or the AI wins, or the game ends in a tie.</li>
  <li>The winner (or tie) will be announced, and the game will end.</li>
</ol>

<h2>Requirements</h2>

<ul>
  <li>Python 3.x</li>
</ul>

<p>No additional libraries are required to run this program.</p>

<h2>Contributing</h2>

<p>Contributions are welcome! If you find any issues or have suggestions for improvements, please feel free to open an issue or submit a pull request.</p>
