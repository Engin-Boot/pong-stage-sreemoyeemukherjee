# Score

## Keeps account of player's score

This module keeps the score of the player
into account. It rewards +2 for every time
the player is able to hit the ball with the
pad. It gives a penalty of -1 everytime the
player misses to hit the ball with the pad

## Acceptance Criteria

### Scenario: Player gets reward score of +2

  Given the player is playing the game

  When the player hits the ball with the pad

  Then increase score by +2

### Scenario: Player gets penalty score of -1

  Given the player is playing the game

  When the player misses and fails to touch
  the ball with the pad

  Then decrease score by -1.
