# Frontend

Based on [BoardGame.io - Tutorial](https://boardgame.io/documentation/#/tutorial)

## Getting Started

You can serve the application TicTacToe from the command line by starting the server with:

```
$ cd containers/app/frontend
$ npm start
```

Although we haven’t built any UI yet, boardgame.io renders a Debug Panel. This panel means we can already play our Tic-Tac-Toe game!

![BoardGame-TicTacToe-001](https://github.com/user-attachments/assets/5ceef030-c375-4b4b-9e6d-3616001695fc)

You can make a move by clicking on ```clickCell``` on the Debug Panel, entering a number between ```0``` and ```8```, and pressing **Enter**. 

The current player will make a move on the chosen cell. The number you enter is the ```id``` passed to the ```clickCell``` function as the first argument after ```G``` and ```ctx```. 

Notice how the ```cells``` array on the Debug Panel updates as you make moves. 

You can end the turn by clicking ```endTurn``` and pressing **Enter**. 

The next call to ```clickCell``` will result in a “1” in the chosen cell instead of a “0”.

**Note**: You can turn off the Debug Panel by passing ```debug: false``` in the Client config.

MORE ...