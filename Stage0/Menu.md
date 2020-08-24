# Module: Menu

## Feature

The game screen will show 4 options :

- Player mode
- Change Background
- Change Ball & Pads
- Quit

## Acceptance Criteria

### Scenario: Player mode is selected

  Given the player wants to start playing with
  the computer

  When the Player mode is selected

  Then show a pop-up asking for the name of the
  player. Once the name is entered, the start button
  shows up and waits for the player to begin.

### Scenario: Change Background is selected

  Given the player wants to change the default black
  background of the game

  When the change background option is selected

  Then take the player to the Store page.

### Scenario: Change Ball & Pads is selected

  Given the player wants to change the default
  white color of the ball and the pads

  When the change ball & pads option is selected

  Then take the player to the Store Page.

### Scenario: Quit is selected

  Given the player wants to quit the game

  When the quit option is selected

  Then take the player out of the game and close
  the game window.
