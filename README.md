Project Name: Minesweeper Project Description
The Minesweeper game is a single-player puzzle game where the player aims to clear a grid of hidden mines without detonating any of them. The player is provided with a grid where some cells contain mines. The objective is to uncover all cells that do not contain mines. If a player clicks on a cell containing a mine, they lose the game. If the player successfully uncovers all non-mine cells, they win. The game provides three difficulty levels: Easy, Normal, and Hard, each with different grid sizes and mine counts.
Key Features
1. Single-player mode with three difficulty levels.
2. Real-time minefield interaction and cell uncovering.
3. Visual representation of the minefield and discovered cells. 4. Win/loss determination and result announcement.
5. Timer to track the duration of the game.
Functional Requirements (FRs)
FR1: At the start of the game, the player can select a difficulty level (Easy, Normal, Hard).
FR2: After selecting the difficulty level, a grid with the corresponding size and mine count is displayed.
FR3: The player can click on any cell to uncover it.
FR4: If the player clicks on a cell containing a mine, the game is over, and all mines are revealed.
FR5: If the player clicks on a cell that does not contain a mine, the cell is uncovered, showing the number of adjacent mines.
FR6: The player can right-click on a cell to flag or unflag it as a suspected mine. FR7: The player wins the game if all non-mine cells are uncovered.
FR8: The game provides a visual timer that starts when the first cell is clicked and stops when the game ends.
User Interface Requirements (UIRs)
UIR1: The main menu displays options for selecting difficulty levels (Easy, Normal, Hard).
UIR2: The grid cells are displayed as buttons that can be clicked to uncover or flagged.
UIR3: A label displays the number of mines remaining, updating as the player flags/unflags cells.
UIR4: The timer is displayed at the top of the game screen, updating in real-time.
UIR5: When the player clicks a mine, all mines are revealed, and a "Game Over" message is shown.
UIR6: When the player successfully uncovers all non-mine cells, a "You Win" message is shown.
UIR7: The "Hit" and "Stand" buttons are replaced with "Restart" and "Exit" buttons once the game ends.