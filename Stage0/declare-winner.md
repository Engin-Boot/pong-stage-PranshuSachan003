# declare-winner

## Feature

this module declares the winner between players.

## Acceptance Criteria

### Scenario: - left hand side player scores last point

  Given - Both players hits the ball through the paddle and
  left hand side player needs one point to win.

  When - ball hits the wall of right hand side player.

  Then -Score of left hand side player increase by one and
  declare as the winner.
  
### Scenario: - right hand side player scores last point

  Given - Both players hits the ball through the paddle and
  right hand side player needs one point to win.

  When - ball hits the wall of left hand side player.

  Then -Score of right hand side player increase by one and
  declare as the winner.
