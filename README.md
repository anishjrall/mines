# Mine Detector Game

A simple Mine Detector Game built using HTML, CSS, and JavaScript where players must safely reveal cells and avoid hidden mines. The game is based on logical reasoning similar to classic grid-based AI environments.

## How It Works

* The game creates a 4×4 grid
* 3 mines are placed randomly each game
* Player clicks cells to reveal them
* Each safe cell shows the number of nearby mines
* If player clicks a mine → Game Over
* If all safe cells are revealed → Player Wins

## Game Logic

* Mine → Lose immediately
* Number → Indicates mines in surrounding cells
* Empty cell → Safe to continue
* Reveal all safe cells → Win

## Features

* Random mine placement
* Score system
* Move counter
* Mine reveal on loss
* Restart game button
* Clean grid UI

## Scoring System

* +10 points for each safe cell revealed
* Score shown live
* Final score shown on win/loss

## Technologies Used

* HTML
* CSS
* JavaScript (Vanilla JS)
