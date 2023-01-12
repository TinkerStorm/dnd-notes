# Arena Insight

> Inspired by specific events of a campaign and the arena tournament that took place that session.

## Probability options

### Dice roll

Choose the dice notation for the roll - `1d20`, `2d6`, etc.

#### Odds or evens

_Shorthand notation for [algebraic notations](#algebraic-equation)_

- Odds = `2N+1`
- Evens = `2N`

#### Multiple

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

#### Integer range

Can be inclusive of the numbers they specify or not - DMs decision.

- `5<>9` - 6, 7, 8
- `5<=>9` - 5, 6, 7, 8, 9
- `5<>=9` - 6, 7, 8, 9
- `5=<>9` - 5, 6, 7, 8

#### Algebraic equation

- Square numbers - `N^2` = 1, 4, 9, 16, 25, etc.
- Prime numbers - `??` = 2, 3, 5, 7, 11, etc.

#### Specific selection

_Can usually be unfair depending on what is selected, **not advised**._

#### Combinations

- Could allow more than one range.
  > `5<>9,12<>=16` - 6, 7, 8; 13, 14, 15, 16
- Or a range, and a multiple.
  > `5<>9;4N` - 6, 7, 8; 4, 8, 12, ...

### Coin flip

- DM selects winning outcome before hand.
- Defer the decision as a bet of sorts.

## DM selections

### Forfeit option

Choose if decision to forfeit is available, and if it should be decided by...
- [A dice roll](#dice-roll)
- [A coin flip](#coin-flip)
- _Available by default_

### Combat knowledge threshold

Advantage could be achieved through use of a select few types of attributes.

- Luck or Charasima - Decrease if successful.
- Intellect or Intelligence - Increase if successful.

> See further down for [Applying 'effects' after insight](#applying-effects-after-insight)

### Additional notes

#### Outcome conflicts

Dice rolls can be merged if they do not directly conflict with each other and condition outcomes can be reversed or flipped around.

| Dice (min) | Forfeit | Knowledge | Description | Guidance |
| ---- | ------- | --------- | ----------- | ---------- |
| `1d12` | x4 | x6 | Linear progression is not linked. Direct conflict with `12`. | Maybe, maybe not. |
| `1d4` | x2 | x4 | Knowledge can only be obtained after the forfeit is offered. | **Not advised.** |
| `1d12` | x4 | >8 | Both can only be attained with `12` at minimum. | Recommended. |

#### Applying 'effects' after insight

- The justification to **increase** on _Intellect_ would be for the player using combat tactics to adjust as needed.
  > Thereby proving themselves as a warrior able to adapt in combat.
- The justification to **decrease** on _Charsima_ would be for the player bribing the arena host, or someone of knowledgable insight.
  > As such, while the charsima may succeed an individual, it would not on observers - for the purpose of balance.
  > 
  > _I don't have a narrative reason as of yet._

Attribute modification can be the DMs decision as for how rewarding / costly it is to the player, and to decide if the effect wears off with time - dependent on the **time scale** of a campaign. Attribute effects can also wear off after another specific event or encounter predefined for the campaign ahead.

#### General notes

Not sure on the direct or indirect implications it would have on a campaign, but it could be something if the odds are balanced appropriately.
