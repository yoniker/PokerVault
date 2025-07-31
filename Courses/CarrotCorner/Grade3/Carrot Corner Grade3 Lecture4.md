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

## Region 1 - Thick value bets

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