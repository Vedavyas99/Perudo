# Perudo - Network Programming Final Project
## Introduction
**Perudo**, also known as **Liar's Dice** is a dice game, where the last player with dice wins.

Each player starts with a hand of dice and rolls them, keeping their rolls secret from the other players. A starting player will make an initial bet and each player will then raise or call when it comes to their turn. 

A *bet* has to have what dice number you are looking for and how many, then a *raise* must increase the ‘how many’, and may change the dice number however they wish. 

To *call* means that you do not believe the last bet was true and their are less then the number to be looked for. In our version, a player may not use ones (1) as a bet, but they count as a wildcard. 

When a player calls and is wrong, they lose a dice. If a player makes a call and is right then the player who made the bet loses a dice. Then after a call is decided, each player re-rolls their hand.
## Features
* Players able to join (usually two) simply by clicking 'run' button in `PlayerClient`.
* Fully functioning game of Perudo (Liar's Dice).
### Important Methods
* `setUpGui()` in the `PlayerClient` class sets up the players buttons and screen. Setup is dependent on which player joined, (aka player 1 or player 2).
* `updateTurn()` in the `PlayerClient` class waits for a number from the server (which is the player's bet), and acts accordingly. It will either turn the dice buttons on, or receive the calculations from a call.
## Getting Started
### Installation and Setup
Clone this repository. This can be done through this command:
`git clone https://github.com/Vedavyas99/Perudo.git`.

### Run
1. Navigate to the correct directory. Here, this will be in: `Perudo > PerudoNetworkingProject > src > PerudoProject`

2. Run the server by clicking 'run' in your respective IDE in `PerudoServer`.
3. Create two players by clicking 'run' twice in `PlayerClient`.

## Demo Video
https://youtu.be/BEXLahrDCyo

## Contributors
* Vedavyas Munugoor
* Tyler Connella 
