# calculate-score

## Feature

this module calculates the score of players.

## Acceptance Criteria

### Scenario: - left hand side player scores

  Given - Both players hits the ball through the paddle.

  When - ball hits the wall of right hand side player.

  Then -Score of left hand side player increase by one and
  gives the ball to left hand side player for hit on the
  ball again.
  
### Scenario: - right hand side player scores

  Given - Both players hits the ball through the paddle.

  When - ball hits the wall of left hand side player.

  Then -Score of right hand side player increase by one and
  gives the ball to right hand side player for hit on the
  ball again.
