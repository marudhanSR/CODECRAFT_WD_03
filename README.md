# CODECRAFT_WD_03

# 🎮 Tic-Tac-Toe Web Application

A responsive and interactive **Tic-Tac-Toe web application** built using **HTML, CSS, and JavaScript**.

The application allows users to choose between **Multiplayer mode** and **AI mode**, making it suitable for both two-player gameplay and single-player gameplay against an automatic computer opponent.

## 🚀 Features

* 👥 **Multiplayer Mode**

  * Player X and Player O can play against each other.
  * Players take turns on the same device.

* 🤖 **AI Mode**

  * Play against an automatic computer opponent.
  * The AI can attempt to win.
  * The AI can block the player's winning move.
  * The AI prioritizes the center and corner cells.

* 🏆 **Winner Detection**

  * Automatically detects the winning player.
  * Highlights the winning combination.

* 🤝 **Draw Detection**

  * Detects when all cells are filled without a winner.

* 🔄 **New Game**

  * Restart the game at any time.

* 📱 **Responsive Design**

  * Works on desktop, tablet, and mobile screens.

* 🎨 **Interactive UI**

  * Clean interface with hover effects and visual feedback.

## 🛠️ Technologies Used

| Technology | Purpose                         |
| ---------- | ------------------------------- |
| HTML5      | Web page structure              |
| CSS3       | Styling and responsive design   |
| JavaScript | Game logic and AI functionality |

## 📂 Project Structure

```text
Tic-Tac-Toe/
│
└── index.html
```

The entire application is implemented in a **single HTML file**, including:

* HTML structure
* CSS styling
* JavaScript game logic
* AI opponent

## 🎮 How to Play

### Multiplayer Mode

1. Open the application.
2. Select **👥 Multiplayer**.
3. Player X starts the game.
4. Player X and Player O take turns.
5. The first player to get three markers in a row wins.

### AI Mode

1. Select **🤖 Play with AI**.
2. You play as **X**.
3. The computer plays as **O**.
4. Click an empty cell to make your move.
5. The AI automatically makes its move.
6. Get three X marks in a row to win.

## 🧠 Winning Conditions

A player wins when they place three identical markers in:

### Horizontal

```text
X | X | X
---------
O |   | O
---------
  |   |
```

### Vertical

```text
X | O |
---------
X | O |
---------
X |   |
```

### Diagonal

```text
X | O |
---------
O | X |
---------
  |   | X
```

## 🤖 AI Logic

The AI follows a simple decision-making strategy:

1. Check whether it can win.
2. Check whether the player can win and block the move.
3. Choose the center if available.
4. Choose an available corner.
5. Choose another available cell.

This provides an interactive single-player experience without requiring a backend or external API.

## 💻 Installation and Setup

No installation or additional dependencies are required.

### Step 1: Clone the repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### Step 2: Open the project

Open the project folder and locate:

```text
index.html
```

### Step 3: Run the application

Double-click `index.html` or open it using a web browser such as:

* Google Chrome
* Microsoft Edge
* Mozilla Firefox

## 🌐 Deployment

The project can be deployed using **GitHub Pages**.

After uploading `index.html` to a GitHub repository:

1. Go to **Settings**.
2. Select **Pages**.
3. Select the required branch.
4. Save the configuration.
5. GitHub will generate a public website URL.

## 📸 Application Preview

The application contains:

* Tic-Tac-Toe game board
* Multiplayer selection
* AI selection
* Current-player status
* New Game button
* Winning combination highlight

## 🔮 Future Enhancements

The project can be extended with:

* 🏅 Score tracking
* 🔊 Sound effects
* 🌙 Dark mode
* ⏱️ Game timer
* 🧠 Multiple AI difficulty levels
* 🥇 Game history
* 👤 Player name customization
* 📊 Statistics and win percentage
* 🎨 Additional themes
* 📱 Progressive Web App support

## 📌 Project Objective

The objective of this project is to demonstrate practical knowledge of:

* HTML page structure
* CSS styling and responsive layouts
* JavaScript event handling
* DOM manipulation
* Arrays and conditional logic
* Game-state management
* Algorithmic decision making
* Interactive web application development

## 👨‍💻 Author

**Marudhan S R**

### ⭐ If you found this project useful

Consider giving the repository a **⭐ Star** on GitHub!
