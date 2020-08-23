# Ball Direction

## Maintains ball direction

The specific direction in which the ball moves
is decided in this module

## Acceptance Criteria

### Scenario: Ball hits any of the 2 vertical walls/pads

  Given player is playing the game

  When ball hits any of the 2 vertical walls / pads

  Then ball moves in opposite horizontal direction
  but in same vertical direction.
  
### Scenario: Ball hits any of the 2 horizontal walls

  Given player is playing the game

  When ball hits any of the 2 horizontal walls

  Then ball moves in opposite vertical direction
  but in same horizontal direction.
