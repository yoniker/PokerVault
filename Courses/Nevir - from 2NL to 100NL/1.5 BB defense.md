
# How to defend your big blind

If you have not studied preflop ranges, there is a high chance that you don't defend your BB well. You can study these ranges with my Range Manager file in the library.

The biggest mistake people make is that they defend the same range against any open sizing. But there is a big difference in your BB defend strategy if your opponent opens 2x or 3x.

The population usually calls too much against 3x opens and not enough against 2x. There are two main reasons why you should call much wider versus small open sizes:

1. You get better pot odds to see the flop.
2. The pot will be smaller, which means it costs you less to see the turn or river.

As a result, you're able to realize your equity more cheaply, giving all your hands extra EV.

Let's look at an example where the BTN cbets 1/3 pot on the flop and 3/4 pot on the turn.

---

## Scenario 1: BTN opens to 2bb

- SB folds, BB calls → Pot = 4.5bb
- BTN cbets 1/3 → 1.5bb, BB calls → Pot = 7.5bb
- BTN barrels 3/4 turn → 5.625bb, BB calls → Pot = 18.75bb
- Total BB investment to see river = 9.125bb

---

## Scenario 2: BTN opens to 3bb

- SB folds, BB calls → Pot = 6.5bb
- BTN cbets 1/3 → 2.145bb, BB calls → Pot = 10.79bb
- BTN barrels 3/4 turn → 8.1bb, BB calls → Pot = 27bb
- Total BB investment to see river = 13.25bb

## Conclusion:

When BTN opens to 3bb, it costs the BB about 4bb more to fully realize their equity compared to a 2bb open. This is why you should defend wider vs smaller opens—you're getting a better price to see the board and realize your equity more cheaply.


## BB's call freq vs open SB

| Open Size   | GTO    | NL50 Pop |
| ----------- | ------ | -------- |
| BB vs 2x    | 71.4%  | 49%      |
| BB vs 2.25x | 64.88% | ?        |
| BB vs 2.5x  | 49.62% | ?        |
| BB vs 3x    | 39.46% | 37%      |

## BB's call freq vs open BTN

|Open Size|GTO|NL50 Pop|
|---|---|---|
|BB vs 2x|56.53%|45%|
|BB vs 2.25x|41.38%|37%|
|BB vs 2.5x|31.43%|35%|
|BB vs 3x|19.15%|34%|

## BB's call freq vs open CO

|Open Size|GTO|NL50 Pop|
|---|---|---|
|BB vs 2x|48.78%|44%|
|BB vs 2.25x|33.85%|35%|
|BB vs 2.5x|25.56%|33%|
|BB vs 3x|16.28%|?|

## BB's call freq vs open HJ

|Open Size|GTO|NL50 Pop|
|---|---|---|
|BB vs 2x|42.7%|43%|
|BB vs 2.25x|30.54%|35%|
|BB vs 2.5x|22.57%|33%|
|BB vs 3x|14.91%|?|

## BB's call freq vs open UTG

| Open Size   | GTO    | NL50 Pop |
| ----------- | ------ | -------- |
| BB vs 2x    | 39.48% | 43%      |
| BB vs 2.25x | 28.61% | 36%      |
| BB vs 2.5x  | 21.2%  | 32%      |
| BB vs 3x    | 14.02% | ?        |
### Conclusions from the above tables
-50NL population are making the most mistakes as BB vs a sb open, when the sb opens to 2BB (and they should call weak hands like Q4o!)-they don't adjust well and call very infrequently =>always open to 2BB from the SB.

Same applies for BU vs BB. They overfold vs a 2BB open (and by the way, vs a 3x open from BU they call way too much)

As CO again BB doesn't call as wide as they should

Nevir recommends to study different reactions vs different open sizings of BU, so I will have a better idea of what to defend as BB. His "Ah-ha" moment came when he compared what he should continue with as BB vs UTG 2BB open versus as a 3BB open.