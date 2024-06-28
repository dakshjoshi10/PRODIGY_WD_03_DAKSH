# PRODIGY_WD_03_DAKSH
This HTML code creates a simple web-based Tic-Tac-Toe game. Here's a breakdown of the components:

### Structure:

1. **HTML Boilerplate**: 
   - The `<!doctype html>` declaration defines the document type and version of HTML.
   - The `<html lang="en">` tag specifies the language of the document as English.

2. **Head Section**:
   - `<meta charset="UTF-8">` sets the character encoding.
   - `<meta name="viewport"...>` ensures the page is responsive and sets initial zoom levels.
   - `<meta http-equiv="X-UA-Compatible" content="ie=edge">` makes the page compatible with older versions of Internet Explorer.
   - `<title>Tic-Tac-Toe</title>` sets the title of the page.
   - `<link rel="stylesheet" href="style.css">` links to an external CSS file for styling.

3. **Body Section**:
   - `<section>`: Contains the main game content.
     - `<h1 class="game--title">Tic-Tac-Toe</h1>`: The main title of the game.
     - `<div class="game--container">`: A container for the game grid, consisting of 9 cells.
       - Each cell is a `<div>` with a `data-cell-index` attribute (ranging from 0 to 8) and the class `cell`.
     - `<h2 class="game--status"></h2>`: A placeholder to display the game status (e.g., whose turn it is, or if someone has won).
     - `<button class="game--restart">Restart Game</button>`: A button to restart the game.

4. **Script Section**:
   - `<script src="script.js"></script>`: Links to an external JavaScript file that will handle the game logic.

### Purpose:
- The HTML defines the structure of a Tic-Tac-Toe game.
- The CSS (in `style.css`) will handle the visual presentation of the game.
- The JavaScript (in `script.js`) will implement the game mechanics and interactivity.
