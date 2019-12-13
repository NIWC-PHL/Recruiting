### Lotto Exercise

Time Limit: 15 minutes

Language/Platform: Your choice


Create an application in any language of your choice that does the following:

1. Generates a lotto ticket (using any method you like)
   * A lotto ticket is a set of three numbers that range from 0-20.
2. Generates a set of winning numbers, and check if the ticket is a winner
3. Repeat step 2 until a winner is found.
4. Optional:
   * Display the number of "days" taken to win the lotto (each time you generate a new ticket it is considered a day)
   * Display the winning numbers / your ticket
   * Display the odds of winning on any single "day"
   * Add a fourth 'bonus' number where you win a bonus prize (can only be claimed if you win the first three)
  

Example lotto tickets (any readable format is acceptable):
```
05-18-20
13 15 19
1-4-17
```

Example output:
```
>.\lotto.php
Your lotto ticket is 04-11-20.
Guessing....
Found a winner after 10395 guesses!
The winning ticket was 04-11-20.
```

```
>.\lotto-bonus.php
Your lotto ticket is 04-11-20-(7).
Guessing....
Found a winner after 10395 guesses!
The winning ticket was 04-11-20-(3).
You did NOT win the bonus multiplier.
```

