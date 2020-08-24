# Levels

## Lets user choose the level, that is, game time

The user gets to choose the game time. The levels
are as follows:

1. 5 minutes
2. 10 minutes
3. 15 minutes
4. Customized time limit

## Acceptance Criteria

### Scenario: User wants to set the level of the game

  Given the user has entered the player name

  When the user selects the level button

  Then show the 4 options and set timer to 5, 10, 15
  minutes if level selected is 1, 2, 3 respectively.
  If level 4 is selected then show pop up box asking
  user to enter time limit in minutes. Set timer as
  per the user entry.
