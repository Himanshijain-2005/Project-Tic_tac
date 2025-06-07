
<h1 align="center">🎮 Tic Tac Toe React Frontend</h1>
<h>project is live at https://himanshijain-2005.github.io/Project-Tic_tac/ <h1>
<p align="center">
  A simple Tic Tac Toe game built with <strong>React.js</strong>. 
  The app demonstrates component hierarchy and state management using class components.
</p>

<hr>

<h2>🚀 Project Setup</h2>

<pre>
# Create React app
npx create-react-app frontend

# Navigate into the project folder
cd frontend

# Start the development server
npm start
</pre>

<hr>

<h2>🧩 Component Structure & Logic</h2>

<p>The app consists of three main components located under the <code>src/</code> folder:</p>

<ul>
  <li><strong>Square.js</strong> - Represents an individual square on the board.</li>
  <li><strong>Board.js</strong> - Contains 9 squares and manages their layout.</li>
  <li><strong>Game.js</strong> - Main game logic implemented as a class component. Maintains game state (e.g., player turns, board values) and handles moves.</li>
</ul>

<p>The component hierarchy and data flow:</p>

<pre>
Game.js (class component, manages state)
  ↓ passes props
Board.js (renders squares)
  ↓ passes props
Square.js (renders individual square)
</pre>

<p><strong>State & Logic:</strong></p>
<ul>
  <li><code>Game.js</code> holds the entire game state, including which squares are filled and whose turn it is.</li>
  <li>Values for each square are calculated and managed inside <code>Game.js</code>.</li>
  <li>These values are passed down as <code>props</code> from <code>Game.js</code> to <code>Board.js</code>, then from <code>Board.js</code> to each <code>Square.js</code>.</li>
</ul>

<hr>

<h2>📁 Folder Structure</h2>
<pre>
frontend/
├── src/
│   ├── components/
│   │   ├── Square.js
│   │   ├── Board.js
│   │   └── Game.js
│   ├── App.js
│   ├── index.js
│   └── ...
├── package.json
└── README.md
</pre>

<hr>

<h2>⚙️ How to Run</h2>

<ol>
  <li>Open terminal and run <code>npx create-react-app frontend</code></li>
  <li>Navigate into the folder: <code>cd frontend</code></li>
  <li>Start the app: <code>npm start</code></li>
  <li>The app will open in your browser at <code>http://localhost:3000</code></li>
</ol>

<hr>

<h2>💡 Key Takeaways</h2>

<ul>
  <li>Class components and state management in React.</li>
  <li>Passing props down the component tree.</li>
  <li>Handling events and updating state to reflect UI changes.</li>
  <li>Component-based architecture for reusable UI pieces.</li>
</ul>

<hr>

<h2>🙏 Acknowledgements</h2>

<p>Inspired by React official tutorial and component design principles.</p>
