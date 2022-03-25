# wordle
Project Wordle

## Game plan

1. Player starts game by clicking the *start* button below the table.

2. Countdown starts when *start* button is clicked.

3. Player inputs in field and submits using *check* button.

4. Program checks if input is valid before checking if letters match.

5. If letter matches and in correct position, the program will return a green letter. If letter matches but in wrong position, return a orange letter. Otherwise, no colour change.

6. Game ends when timer runs out, or attempts limit is reached.

Restart button shows after game ends. Player can click *Try again* button to start the game again (clearing all fields, colours etc. and resetting the timer.)

## functions used

1. interval function used to set a countdown timer

2. variables used to reset the countdown timer (i.e. resetTimer). 

```javascript
//resetTimer to true
        resetTimer = true;
```
3. innerText used to update messages to the player

4. nested for loops to clear fields and reset the game

5. grid for layout of page


