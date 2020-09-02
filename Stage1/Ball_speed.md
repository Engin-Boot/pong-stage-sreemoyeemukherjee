# Ball Speed

## Feature

Change speed of ball depending on whether default or harder
paddles are being used.

## Acceptance Criteria

### Scenario: Ball hits either horizontal or vertical, any wall

  Given the pong game is ON and the paddles being used
  in the game are default paddles

  When ball hits any wall

  Then maintain same speed of ball

### Scenario: Default paddles are being used

  Given the pong game is ON and the paddles being used
  in the game are default paddles

  When ball hits any paddle

  Then maintain same speed of ball
  
### Scenario: Harder paddles have been selected by user

  Given the pong game is ON and the paddles being used
  in the game are harder paddles

  When ball hits any paddle

  Then speed of ball doubles.
