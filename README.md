![Languages](https://img.shields.io/badge/-C++-%2303a9f4?style=for-the-badge&logo=cplusplus) 
![SFML](https://img.shields.io/badge/SFML-brightgreen?style=for-the-badge&logo=sfml)

# Introduction

This project is a simple implementation of John Conway's "Game of Life".   
  
"The Game of Life, is a cellular automaton devised by the British mathematician John Horton Conway in 1970. It is a zero-player game, meaning that its evolution is determined by its initial state, requiring no further input."

## Rules
Every cell interacts with its eight neighbours, which are the cells that are horizontally, vertically, or diagonally adjacent.  
At each step in time, the following transitions occur:
  
1 - Any live cell with fewer than two live neighbours dies, as if by underpopulation.  
2 - Any live cell with two or three live neighbours lives on to the next generation.  
3 - Any live cell with more than three live neighbours dies, as if by overpopulation.  
4 - Any dead cell with exactly three live neighbours becomes a live cell, as if by reproduction.
  
# How to use
This project requires C++20 and SFML (Simple and Fast Multimedia Library)
  
- [How to setup SFML](https://www.sfml-dev.org/tutorials/2.5/start-vc.php)
  
# I have everything setup, now what?
Run the code, enter the size of your grid and the number of generations, and watch it do its magic!
  
<p align="center">
  <img src="https://github.com/MiTsSsS/John-Conway-Game-of-Life/blob/master/GoLExecGif.gif" width = 55%; height=55% />
</p>
