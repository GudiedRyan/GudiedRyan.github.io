+++
title = "Sudoku Game and Solver"
cover = "Sudoku-img.png"
coverCaption = ""
tags = []
keywords = []
description = "Play a Sudoku game or get a hint on one you're stuck on."
showFullContent = true
readingTime = false
hideComments = false
color = "" #color from the theme settings
+++

Before starting my Masters program, I challenged myself to write an algorithm that could solve Sudoku puzzles. I designed a backtracking algorithm to efficiently solve puzzles. 

Years later I decided to return to the project and follow my initial goal of turning it into a full stack application. Utilizing Claude code, I paired a ReactJS frontend with a flask backend. 

The full game is hosted [here](https://sudoku-solver-xc88.onrender.com/).

I have some ideas for additional enhancements down the line. One of note is adding the ability to take a picture of a puzzle and upload it to the website. Utilizing a text processing model, the puzzle would then be loaded into the board.

Tech used:
Python, Flask, React, CSS, Render