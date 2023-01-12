# Probability options

## Dice roll

Choose the dice notation for the roll - `1d20`, `2d6`, etc.

### Odds or evens

_Shorthand notation for [algebraic notations](#algebraic-equation--mathematical-ranges-or-constants)_

- Odds = $2n+1$
- Evens = $2n$ or $f(n)=n\sin{n}$ [Ref (`math.stackexchange.com`)](https://math.stackexchange.com/a/3899831)

### Multiple

> A multiple within the bounds of the dice allowed
  > At least half of the max value for two possible outcomes
  
- Multiple of 5 on d20 = 5, 10, 15 & 20 success = $5n$
- Multiple of 4 on d12 = 4, 8 & 12 for success = $4n$

Multiples in the equations here could be expressed as...

- $4n$ (`4n`) to generate all possible outcomes
- $n / 4$ (`n / 4`) to only allow the result of `n` to be a whole number when the division is attempted
  > Effectively $\lfloor{n / 4}\rfloor = n / 4$ = `floor(n / 4) == n / 4`
- $n\mod4$ (`n % 4`) to only allow `0` as the true outcome via modulus division
  > Effectively $n\mod4=0$ (`n % 4 == 0`)

### Integer range

Can be inclusive of the numbers they specify or not - DMs decision.

> This table utilizes [Interval notation (`undergroundmathematics.org`)](https://undergroundmathematics.org/glossary/interval-notation) for it's shorthand descriptions in plain text. If read using the wrong context, they can be mistaken for coordiates _as noted on the referenced page_.

|      Range Type | Notation              | Shorthand          | Matches       |
| ---------------:|:---------------------:|:------------------:| ------------- |
|       Exclusive | $\{n:5 <   n >   9\}$ | $(5,9)$ - `(5,9)`  | 6, 7, 8       |
|  Inclusive open | $\{n:5 \le n \ge 9\}$ | $[5,9]$ - `[5,9]`  | 5, 6, 7, 8, 9 |
|  Inclusive left | $\{n:5 <   n \ge 9\}$ | $(5,9]$ - `(5,9]`  | 5, 6, 7, 8    |
| Inclusive right | $\{n:5 \le n >   9\}$ | $[5,9)$ - `[5,9)`  | 6, 7, 8, 9    |

There are 'range types' for left only and right only, which would omit the operand for the other part of the range, and instead be noted as `>` / `>=` / `<` / `<=` by themselves (`5<` or `>=9`) or by Interval notation (i.e. `[5` or `9)`).

### Algebraic equation / mathematical ranges or constants

- Square numbers - $n^2$ = 1, 4, 9, 16, 25, etc.
- Prime numbers - $P$ = 2, 3, 5, 7, 11, etc.

### Specific selection

_Can usually be unfair depending on what is selected, **not advised**._

### Combinations

- Could allow more than one range.
  > $[5,9] + [12,16)$ - 6, 7, 8; 13, 14, 15, 16
- Or a range, and a multiple.
  > $[5,9] + 4N$ - 6, 7, 8; 4, 8, 12, ...

## Coin flip

- DM selects winning outcome before hand.
- Defer the decision as a bet of sorts.
  > Deferral would allow the player to choose what outcome they want to achieve - matching that outcome is a success for them.
