# Stop

## Stops the game

Stops and resets the timer, stores the score against the
entered player name and ends the game.

## Acceptance Criteria

### Scenario: Stop button pressed by user

  Given the user is playing the game

  When user presses the stop button

  Then stop and reset the timer, store current score
  against the player's name and end the current game.
  
### Scenario: Timer ends depending on level selected

  Given the user has been playing the game for some time

  When time runs out according to the user selected level

  Then stop and reset the timer, store current score
  against the player's name and end the current game.
