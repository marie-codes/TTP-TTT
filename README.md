# TTP - Tic Tac Toe



### Description:

An iOS mobie application game of Tic Tac Toe that allows the User to play against AI. 


### Directions:

1) Clone or download the github repository.
2) Run the code in the simulator in XCODE versions 10.0+; best viewed using iPhone6+ mode.
3) Begin playing the game as Player 1 (X's) by clicking in one of the boxes within the grid. 
4) Once your 'X' is placed, the AI (computer) will automatically respond as Player 2 (O's).
5) Continue to Play versus AI.
6) When the game is completed, the Players' Scores will update at the top of the grid.
7) Once the game is completed or to start the game over, simply click the green 'RESET' button below the grid. 
8) Play until your heart's desire!


### Resources:

Created by referencing tutorial: 'Build Tic Tac Toe with AI Using Swift' by Keith Elliot.

- Apple SpriteKit (https://developer.apple.com/reference/spritekit) framework
- Apple GamePlay Kit (https://developer.apple.com/reference/gameplaykit) framework
- Apple UIKit

● SpriteKit uses SKNodes to draw the UI elements in storyboard and SKScene / SKView to animate and render gaming functionality. 
● GamePlay Kit provides access to the AI Player via StateMachine, using properties inherited from GKGameState states: StartGameState, ActiveGameState, and EndGameState. ● An instance of the GKMinmaxStrategist Class and Protocols: GKGameModel, GKGameModelUpdate, and GKGameModelPlayer provides access and updates the functionality for the AI (computer0. Set the maxLookAheadDepth to control how strong our AI component will be during gameplay.
