# 37Rdoku
Sudoku-like game based on reversible cellular automata 37R. See also GitHub repository giulioprisco/ECARdoku.

This is a simple Sudoku-like game based on the reversible extension (37R) of Wolfram’s elementary cellular automata Rule 37. The code is in the GitHub repositories giulioprisco/ECARdoku and giulioprisco/37Rdoku, with links to a live game. First, the game fills a square board of grey cells with random black/white clues that ensure there is a unique solution. Then the player has to complete the board using Rule 37R.

To solve the game, apply Rule 37R in both the forward and backward directions. Remember that the board wraps upon itself like a cylinder (the last column comes before the first and the first comes after the last). Try and find groups of cells that can be completed, consistently with the rules, in only one way. For larger boards, finding the unique solution can be quite difficult without computer assistance. The game generates new random clues on request if the player gets stuck.

This game was developed with AI assistance from Grok 4.

Pictures:

- 37RdokuiPhone.jpeg
- 37RdokuiPad.jpeg