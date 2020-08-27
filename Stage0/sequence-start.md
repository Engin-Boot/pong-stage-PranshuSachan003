# Interaction Sequences

## Startup Sequence

The startup sequence is follows as : start_game -->timer_start-->collision_with_wall-->calculate_score-->declare_winner-->quit_game

## Movement Initiation

Initially players starts the game, the ball triggers from left to right (I am giving first chance to player at left side to hit
the ball) and when first hit occurs on the ball, the timer starts. If ball hits on first player's wall, a point (may change)
increases for second player's scorecard, else ball hits on second player's wall,  a point (may change) increases for first player's
scorecard. Who ever scores 10 (may change) Points first, declared as winner of the game. If timer exceeds 2 hr ( may change) the games
terminates automatically, else player has asked for quit the game or restart the game.

## One score

When collision_with_ball module finds collision then it calls the calculate_score module.
