## Raising and beyond

What hands should I raise on the flop and why & What should I do with each type of hand on further streets after I get called

There are 5 classes of hands that I can *consider* raising on the flop:
1. Thick value region (Sets/flushes/straights)
2. Thin value region (Top pair decent kicker/Top pair bd flush draw/ mediocre overpair to a low board) - by raising those at some frequency for value i can also raise more bluffs and be more balanced
3. High EV bluff region: OESD, Flush draws, Nutshots (gutshot to the nuts)+good pair draw. It's only loosely a bluff - I have a ton of equity.
4. Hybrid region: low pair+low kicker for example, hands that have some attributes of value betting, bluffing and denial all at the same time 
5. Low-EV bluff region: BD flush+ BD straight,bad gutshot + overcard (aka pair draw) - I need those to forece villian to call with middling hands (otherwise he can fold those pure) - which would in turn reduce the EV of my region 1 hands


Unlike region 1 which is pure, regions  2+3 are mixing,
Humans are not finding as many raises as the solver especially in the regions 2,4,5.

Now let's dive into the different regions:

## Region 1 - Thick value region

In some cases the solver will x/r pure my thick value hands, in some cases it will mix. To see when and how to mix - practice. In general, the factors that I need to take into account when considering how to mix the hand are:
1. How polorised villian is: If he bets huge, even bottom sets can mix calling and raising
2. Board texture: Even nut flush on a monotone board doesn't x/r pure
3. Blockers: On JJ7, 77 doesn't raise pure, as I block villian's middling hands and so he can still have air

When studying, if I thought it was mixed and it's pure, I can look at the ev difference to determine how big of an error it was

### Cobra's rule
 Since the check-raisor's range is abundant in high equity bluffs,after the check/raise was called:

1. a wet turn equalises the nut advantage (as both players could have a draw) but gives the check/raiser a big range advantage.

2. On dry turn, the check/raiser still have the nut advantage, but the range advantage is  the caller's (a lot of the check/raiser hands bricked)
So: Wet turn -> bet frequently and small, dry turns -> bet infrequently and large. 

## Region 2 - thin value region

Thin value bets are raising similar to the global X/R frequency(!), where the other four regions X/R (usually) more than the global X/R frequency.


After getting called with middling hands like A8 on A94 we usually don't want to continue to aggress - as we don't want to build gigantic pots with those middling hands. We don't mind "bloating" the pot on the flop, as long as we don't lose our minds and continue building huge pots later with those hands.

On the turn with this region, if our range wants to bet big or check we always check, if our range wants to bet small or check, then we can sometimes bet small


## Region 3 - High EV bluff region
Those hands will almost always bet more frequent than the global X/R frequency

### On the turn
on a wet turn, all of our X/R region bets small, so those this hands too.

On a dry turn, our range bets infrequent and big - so are those hands.

## Region 4 - Hybrid region
Marginal made hands which benefit from fold equity and retain decent equity when called.
The more vulnerable those hands are (and the weaker they play as a call), the more often they will opt to raise.

### On the turn
We find ourselves on the turn with a mediocre hand but a polarised range. Those hands become mediocre (tier 6-carrot poker school 2) bluff candidates - on the turn it becomes a low ev bluff.
#### Brick turns:
so on a brick turn we can bet those hands (which usually have 5 outs to a nutted hand- therefore some ev - but yeah it's a bluff now)
#### Wet turn

Depending on the turn, if it's a horrible turn for our range (for example flop was monotone spade and the 4th card is another spade) then we give up those bluffs

## Region 5 - Low-ev bluffs
Those hands are usually indifferent between the options of raising/calling/folding (sometimes indifferent between raising and folding).

### On the turn
Having raised on the flop,don't bluff again with low-ev hands that missed on a neutral or unfavorable turn card - it's a horrible blunder to bluff with those hands at those spots.



