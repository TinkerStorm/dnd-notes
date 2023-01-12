# Probability options

## Dice roll

Choose the dice notation for the roll - `1d20`, `2d6`, etc.

### Odds or evens

_Shorthand notation for [algebraic notations](#algebraic-equation)_

- Odds = `2N+1`
- Evens = `2N`

### Multiple

> A multiple within the bounds of the dice allowed
  > At least half of the max value for two possible outcomes
  - Multiple of 5 on d20 = 5, 10, 15 & 20 success = `5N`
  - Multiple of 4 on d12 = 4, 8 & 12 for success = `4N`

Multiples in the equations here could be expressed as...
- `4 * N` to generate all possible outcomes
- `N / 4` to only allow the result of `N` to be a whole number when the division is attempted
  > Effectively `~~(N / 4) == (N / 4)`
- `N % 4` to only allow `0` as the true outcome via modulus division
  > Effectively `N % 4 == 0`

### Integer range

Can be inclusive of the numbers they specify or not - DMs decision.

- `5<>9` - 6, 7, 8
- `5<=>9` - 5, 6, 7, 8, 9
- `5<>=9` - 6, 7, 8, 9
- `5=<>9` - 5, 6, 7, 8

### Algebraic equation

- Square numbers - `N^2` = 1, 4, 9, 16, 25, etc.
- Prime numbers - `??` = 2, 3, 5, 7, 11, etc.

### Specific selection

_Can usually be unfair depending on what is selected, **not advised**._

### Combinations

- Could allow more than one range.
  > `5<>9,12<>=16` - 6, 7, 8; 13, 14, 15, 16
- Or a range, and a multiple.
  > `5<>9;4N` - 6, 7, 8; 4, 8, 12, ...

## Coin flip

- DM selects winning outcome before hand.
- Defer the decision as a bet of sorts.
  > Deferral would allow the player to choose what outcome they want to achieve - matching that outcome is a success for them.